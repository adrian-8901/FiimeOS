# FiimeOS
This is a new rom with the goal is smooth and stable

# Syncing the source
1. Run this command with your env setuped computer.
```bash

# Initialize local repository
repo init -u https://github.com/adrian-8901/FiimeOS.git -b 11

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
### Build ###
2. Run this command 
 ```bash
 # Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
 ```
 ### By @P4042 and @fiimecn in telegram ###
 
 
 
