```bash
pacman -S python-pip python-virtualenv
ansible-galaxy install -r galaxy-requirements.yml
ansible-playbook dotfiles.yml
```

# Dotfiles

Settings and Preferences for transfer between machines

## Requirements
- SSH / GPG keys installed
- Correctly setup `~/.dotfiles` directory

## Usage
1. Run `./scripts/setup.sh` to setup local environment
2. Run `./scripts/deploy.sh`
