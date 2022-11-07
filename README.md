# aliceOS | Hello, Alice.
Yet another android rom based on AOSP.

### Requirements
- Around 500gb disk space.
- Around 16GB RAM

### SYNC ###
```bash
repo init -u https://github.com/aliceOS-AOSP/manifest -b Maze
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
