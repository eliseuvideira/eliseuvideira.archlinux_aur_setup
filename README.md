# Arch Linux AUR Setup

Install AUR Helper on Arch Linux Distros

## Requirements

It should work on any archlinux distribution

## Role Variables

| Variable | Required | Default | Choices         | Comments                             |
| -------- | -------- | ------- | --------------- | ------------------------------------ |
| state    | no       | present | present, absent | present to install, absent to remove |

## Example Playbook

    - hosts: archlinux
      roles:
         - { role: eliseuvideira.archlinux_aur_setup, state: "present" }

## License

MIT
