# Upate scripts for the Data Arena Virtual Machine

## Usage:

Run `sudo updateDAVM` and enter the root password to update DAVM examples, user settings and system settings. This script attempts to connect to `code.research.uts.edu.au` to pull repositories. Failing that, it tries to pull repositories from `https://www.github.com/UTSDataArena`.

Run `sudo updateSW` and enter the root password to update the DAVM and system software: ie omegalib, Equalizer, bino, drishti, etc. This script uses the existing remotes in each repository on the DAVM.
