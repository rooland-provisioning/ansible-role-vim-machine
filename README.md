# vim-machine

This role installs and configures Vim.

## Requirements

This role depends on package manager. For Linux it is [APT](https://wiki.debian.org/Apt) and for OS X it's [Homebrew](http://brew.sh).

## Role Variables

- **vim_machine.local_history_path** _optional_ Directory where local history of files will be stored

## Example Playbook

~~~yaml
    ---
    - hosts: stage
      roles:
        - role: rooland-provisioning.atom-editor
          tags:
            - atom
            - editor
~~~

## License

BSD

## Author Information

I am usually idling on Freenode as lipoqil
