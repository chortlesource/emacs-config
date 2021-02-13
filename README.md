# Chortle's Linux Emacs configuration

## ABOUT

The following is a personal configuration file I use for emacs. It will download, compile and install most packages I need. It is pretty buggy at this point because frankly emacs 25.3 has issues. Most notably with PGP and TLS 3.1.

Why not use a later version? I use Debian because I need a solid system and currently this is the latest version available in the stable repo's. I could install from source and migrate or even use a later version from snaps but I generally don't care enough to warrent breaking it further.

In conclusion this is only available on github in the event of hardware failure and I need to get another system up and running quickly. I would suggest you avoid and find a different config.

## DEPENDENCIES

* emacs 25.3.2

## INSTALLATION

As suggested I haven't got this installing flawlessly at this point. Typically when I first install I receive errors on the first four attempts to load. Eventually things compile properly; which is not the kind of reassuring statement I like to read.

* Backup your current emacs configuration. (ie `.emacs` and `.emacs.d`)
* `rm -rf ~/.emacs ~/.emacs.d`
* `git clone git@github.com:chortlesource/emacs-config.git`
* copy the .emacs and .emacs.d from the emacs-config folder to your home directory
* run `emacs` a few times until stuff stops breaking.
