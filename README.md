# Restoring-Ubuntu-Desktop

### This document is to help anyone faced with the challenges of restoring their ubuntu desktop, after installing a different desktop environment.
- Firstly you need to update your package manager by running this command;
- After updating your package manager, you need to install back your ubuntu-desktop. This is in case you deleted it.
```bash
sudo apt update
```
- But i would advice you run the command even if you didn't, one never knows.
```bash
sudo apt install ubuntu-desktop
```
- After successfully installing your ubuntu-desktop, you need to now install your display manager, using this command
```bash
sudo apt install gdm3
```

- Finally, you set this displaay mannager you just install to your default session using this command;
```bash
sudo dpkg-reconfigure gdm3
```
- Wow! your good to go.
  - just finalize the process using;
```bash
sudo reboot
```
- This command wil reboot your computer.\
  - you have any issue drop in the Issues tab, i will attend to it.
  - In case of any difficulty, you drop it in the issue tab.

# If this was helpful, please star the repository
## THANKS
