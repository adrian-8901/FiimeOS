# FiimeOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/adrian-8901/FiimeOS.git -b 11


# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch 

# Build the code
$ brunch device-codename
```

### By @P4042 and @fiimecn ###
