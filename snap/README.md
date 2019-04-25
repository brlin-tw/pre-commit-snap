# Unofficial Snap Packaging for pre-commit
<!--
	Use the Staticaly service for easy access to in-repo pictures:
	https://www.staticaly.com/
-->
![Logo of pre-commit](gui/logo.256px.png "Logo of pre-commit")

**This is the unofficial snap for pre-commit**, *"A framework for managing and maintaining multi-language pre-commit hooks"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `pre-commit` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/pre-commit-snap.svg "Build Status of the `pre-commit` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/pre-commit-snap)

![Screenshot of the Snapped Application](local/screenshots/precommit-run-allfiles-result.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

<!-- Uncomment and modify this when you have published the snap to the Snap Store
## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install --channel=edge --devmode pre-commit
    #sudo snap install --channel=beta pre-commit
    #sudo snap install pre-commit
    
    # Connect the snap to essential security confinement interfaces #
    ## (Proper reasoning for connecting _plug_name_) ##
    sudo snap connect pre-commit:_plug_name_
    
    # Connect the snap to optional security confinement interfaces #
    ## (Proper reasoning for connecting _plug_name_) ##
    sudo snap connect pre-commit:_plug_name_
    
    # Launch the application #
    pre-commit
    snap run pre-commit # If you have another existing installation

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/pre-commit)
-->

## What is Working
* Launch
* `pre-commit run --all-files` on `pre-commit/pre-commit`
* `pre-commit run --all-files` on a repository that has arbitrary depending command hook
* `pre-commit.validate-config`

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/pre-commit-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/pre-commit-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>
