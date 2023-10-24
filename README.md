## Repo Init ##
```bash
repo init -u https://github.com/Nothing-Phone-2-kernel-development/manifest.git -b lineage-20
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
## Building Kernel ##
```bash
./build.sh taro
```
