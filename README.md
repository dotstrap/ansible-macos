ansible-osx
=========
[![Build Status](https://travis-ci.org/mkwmms/ansible-osx.svg?branch=master)](https://travis-ci.org/mkwmms/ansible-osx)

Bootstrap, configure, & manage [OS X].

Installation
------------

```
ansible-galaxy install mkwmms.osx
```

Requirements
------------

[OS X].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: mkwmms.osx
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]

[@mkwmms]: https://github.com/mkwmms
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mkwmms/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[OS X]: http://www.apple.com/osx/
[pure]: https://github.com/sindresorhus/pure
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
