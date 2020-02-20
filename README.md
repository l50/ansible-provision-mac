# ansible-provision-mac
This is used to provision and maintain my macOS systems. I've built it for me and have not given any thought to creating a generic and user-friendly solution. Of course, you can feel free to check it out and modify it for your systems if it does things you find helpful. If you are looking for a more generic solution for this problem, consider taking a look at [strap](https://github.com/MikeMcQuaid/strap).

## Requirements
- Ansible
- Ansible Galaxy

## Dependencies
- [SpaceVim](https://galaxy.ansible.com/l50/ansible-spacevim)
- [logrotate](https://github.com/nickhammond/ansible-logrotate)

## Installation
Install external dependencies with Ansible Galaxy:
```
ansible-galaxy install -r requirements.yml
```

## License
MIT

## Author Information
This role was created in 2020 by [Jayson Grace](https://techvomit.net)