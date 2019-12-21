# Ansible Role: virtio

[![Build Status](https://img.shields.io/travis/sbaerlocher/ansible.virtio.svg?branch=master&style=popout-square)](https://travis-ci.org/sbaerlocher/ansible.virtio) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtio-blue.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/virtio) [![Ansible Role](https://img.shields.io/ansible/role/d/25032.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/virtio)

## Description

This Ansible role installs the VirtIO driver and updates it also for new releases under Windows.

## Installation

```bash
ansible-galaxy install sbaerlocher.virtio
```

## Requirements

None

## Role Variables

| Variable            | Default                                                                                         | Comments (type) |
| :------------------ | :---------------------------------------------------------------------------------------------- | :-------------- |
| virtio_win_iso_url  | <https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/virtio-win.iso> |                 |
| virtio_win_iso_name | virtio-win.iso                                                                                  |                 |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - sbaerlocher.virtio
```

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)
- [Petr Ruzicka](mailto:petr.ruzicka@gmail.com)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2020, Simon Bärlocher
