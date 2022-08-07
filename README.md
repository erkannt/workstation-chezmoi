# Restore workstation

1. Upgrade system
   - `xbps-install -Su`
1. Install chezmoi/ansible restore requirements
   - add lastpass to firefox and log in
   - `xbps-install git ansible zsh vim chezmoi`
1. Chezmoi setup
   - `chezmoi init erkannt/workstation-chezmoi`
   - `chezmoi apply`
1. Ansible
   - launch `zsh` for access to aliases
   - `cd ~/workstation-setup`
   - `ans all.yaml`
1. Restore data from pongo
   - `restore`
1. Manual steps
   - nvidia drivers: `sudo ubuntu-drivers autoinstall`
   - login to apps:
     - spotify
     - slack
     - chromium
     - firefox sync

