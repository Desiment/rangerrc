# rangerrc

Personal Ranger configuration, used as the `dotfiles/config/ranger` submodule
of [deskit](https://github.com/Desiment/deskit). The explicit deployment
mapping is `dotfiles/config/ranger/` -> `~/.config/ranger/`; cloning does not
change the live configuration.

This repository starts with the current `commands.py`, `rc.conf`, `rifle.conf`,
and `scope.sh` as a basis for future customizations. Ranger's
`commands_full.py` is a reference copy of upstream commands, not a loaded
configuration file, so it is not included. Local history, bookmarks,
credentials, and generated state must not be committed.
