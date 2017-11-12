# Ansible Role: virtio

## Description

## Installation

```
$ ansible-galaxy install sbaerlocher.virtio
```

## Requirements

Ansible 2.4 or later

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| virtio_win_iso_url | https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/virtio-win.iso | |

## Dependencies

Windows 64 bit (amd64) (x64)

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.virtio
```

## Changelog

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
* [Petr Ruzicka](mailto:petr.ruzicka@gmail.com)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher