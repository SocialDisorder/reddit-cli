# reddit-cli
Scrape reddit articles from terminal

#### How does it work?

![alt text](usage.gif "How does it work")

#### You will need to install these programs:
**ueberzug** (Überzug is a command line util which allows to draw images on terminals by using child windows.)
**pip** (pip is the package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.)

from pip you need to install: "pip install {name of package}"
**bs4** (Beautiful Soup is a library that makes it easy to scrape information from web pages.)
**getch** (The getch module does single-char input)

#### Configuration
after first run following folder will be automaticly created:
*~/.config/reddit-cli/threads.txt*
you can add or remove any reddit thread you like

#### Usage
this program uses vim like keybinding
**j** move to next post/comment
**k** move to previous post/comment
**q** exit program/go back to posts
**c** show comments
**:** you will be prompt to type number of post/comment you want to see
