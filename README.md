ansible-macos
=========
[![Build Status](https://travis-ci.org/dotstrap/ansible-osx.svg?branch=master)](https://travis-ci.org/dotstrap/ansible-macos)

Bootstrap, configure, & manage macOS.

Installation
------------

```
ansible-galaxy install dotstrap.osx
```

Requirements
------------

macOS

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: dotstrap.osx
```

License
-------

MIT

Author Information
------------------

[@mwilliammyers]

[@mwilliammyers]: https://github.com/mwilliammyers
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[macOS]: http://www.apple.com/osx/
[pure]: https://github.com/sindresorhus/pure
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
