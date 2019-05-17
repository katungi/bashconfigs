# README.md
This repository is to store my bash settings and configs.
Feel free to fork it and edit it as you wish.  

**NOTE**  
Please read the through the code and don't just copy and paste. I am not liable if you break your system.  

## Installation  
If you have looked through the code and choose to install it in your system follow these steps:  

Create a backup of your files by renaming them like so:  

`mv .bashrc .bashrc.backup && mv .bash_profle .bash_profile.backup`  

Once that is finished, simply clone the repository and copy all the files to you home directory.  

```git clone https://github.com/keystroke3/bashconfigs && cd bashconfigs && cp .* ~/ ```

When this is done, you can apply the changes by executing  
`exec /bin/bash -l` for bash or `exec /bin/zsh -l` for zsh.

## options  
There are two options for the bash prompt. One with emojis and the other made of blocks. The file `.bash_prompt.blocks` file will look like this: 

![Blocks prompt screeshot](https://raw.githubusercontent.com/keystroke3/bashconfigs/master/screenshots/blocks.png "blocks prompt")

If you wish to have this as your prompt, you can simply run:

`mv ~/.bash_prompt.blocks .bash_prompt`  

and then apply changes.

If you wish to have the blocks, you can run:  

`mv ~/.bash_prompt.emoji .bash_prompt`  

Bloks:

![Blocks prompt screeshot](https://raw.githubusercontent.com/keystroke3/bashconfigs/master/screenshots/emoji.png "blocks prompt")

