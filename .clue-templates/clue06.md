### Clue 6: Make Me a Sandwich ###

https://xkcd.com/149/

#### `sudo` ####

Linux has the concept of a `root` user, which is similar to the administrator
user on Windows. This user is sometimes called the super user. If you want to
do something as the super user, but stay logged in as yourself, there is a 
command for that: `sudo`. It stands for "super-user do".

#### Installing Software ####

Sometimes you need a new program. To install software on some versions of Linux
(Ubuntu and Debian), you use the command `apt-get`. On other versions (Fedora,
CentOS) you use the command `yum`. On Mac, you should use [Homebrew](brew.sh) Let's install a text editing program
called `vim`.

    apt-get install vim
    
You should get an error message asking if you are root. This means you don't
have the ability to install software. Instead, try

    sudo apt-get install vim
    
Now we have the ability to edit files. Try

    vim README.md
    
from the `scavenger-hunt` directory. Some of the commands for `vim` are a little
strange. For now, just type `:q!` to quit.


#### Finding Clue 7 ####

Suppose you have a file open in `vim` and want to go to line 5. Your next hint is the command that accomplishes that task. _(Note that there are several correct answers; you just need to indicate one of them.)_
