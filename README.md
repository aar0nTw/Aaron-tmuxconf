Aaron's tmux config
===================

![image](http://cl.ly/image/1K030L2E273S/Screen%20Shot%202012-10-29%20at%203.16.48%20PM.png)

Install tmux 1.5 or greater.  This conf has been tested with tmux 1.5

First checkout this repo then symlink it to your home directory.

$ ln -s ~/{LOCATION OF YOUR REPOSITORY}/tmux.conf ~/.tmux.conf

If you want to have the status of your battery
```
$ ln -s ~/{LOCATION OF YOUR REPOSITORY}/power.sh /usr/local/bin/
```

If you want use the mac pastebuffer command , like `pbcopy`,`pbpaste` 
```
brew install reattach-to-user-namespace
```
