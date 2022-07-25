# Restore workstation

1. Install chezmoi/ansible restore requirements
  - add lastpass to firefox and log in
  - `apt install git ansible zsh`
  - `sh -c "$(curl -fsLS https://chezmoi.io/get)"`
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

