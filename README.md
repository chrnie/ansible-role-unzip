# Ansible Role: unzip

An Ansible role for managing unzip.


## Requirements

None.


## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    unzip_state: latest

possible values: latest, present, absent


## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - chrnie.unzip


## License

MIT / BSD


## Author Information

Created in 2017 by Christoph Niemann, https://github.com/chrnie
