# crtnb_ipynb
Bash script to create useable .ipynb notebook without launching jupyter notebook.  
Download and copy crtnb to `~/.config`  

``
$ git clone https://github.com/asbiebly/crtnb_ipynb.git ~/.config && cd ~/.config && rm -rf .git README.md
``

## Create Executable
Steps to create executable named crtnb
  
``
$ sudo ln -s ~/.config/crtnb /usr/local/bin/crtnb
``
  
``
$ chmod +x ~/.config/crtnb
``

## How to use the executable
``
$ crtnb /path/where/want/to/save.ipynb
``
