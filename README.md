# Ansible Role: virtio

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
