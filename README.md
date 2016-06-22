# vim-machine

This role installs and configures Vim.

## Requirements

This role depends on package manager. For Linux it is [APT](https://wiki.debian.org/Apt) and for OS X it's [Homebrew](http://brew.sh).


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
