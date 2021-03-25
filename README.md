# Debian sys info

clone the repo with git, add the minifetch file to your path, execute

`git clone https://github.com/Merazi/minifetch`

and then you can do a symbolic link to it, be sure to add it to a directory that is part of your $PATH variable, here's an example:

`sudo ln -s ~/minifetch/minifetch /usr/local/bin/minifetch`

# Dependencies

- bash (it is a bash script, but it may work on other shells like zsh or fish, I have not tested it :P)
- wmctrl (for getting the window manager name)
