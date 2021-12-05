# timedot-vim
timedot-vim is a vim-plugin to enhance working with hledger timedot files.

## Introduction
What's a timedot file? you ask? It is an elegantly simple file-format that can be parsed by hledger to keep track of/ budget/ invoice your time. timedot is perfect for recording time spent on things where you don't need clock-in clock-out precision, you just want to quickly make note of how much time you spent on various activities, per day. Because the format is so concise and human-read/writable, you are more likely to jot down time-spent notes. Adding or correcting entries after-the-fact is a quick edit away.

This plugin adds syntax hilighting and includes a handy shell script to make things even easier. Both things are really just a start on the features I imagine for this project (see issues) but I use both, daily, and it works great over here. Ideas and especially Pull-Requests are especially welcome.

## Install
You probably have a favorite way to install vim plugins, but mine is to use the built-in vim/pack method.
```
cd ~/.vim/pack/plugins/start
git clone https://github.com/linuxcaffe/timedot-vim.git
```
and voila! installed! Now, on editing a `*.timedot` file, you should see improved syntax hilighting. 

To install the handy `t.` script, you can copy it to, or link it to somewhere in your $PATH and make it executable. I use something like;
```
ln -s ~/.vim/pack/plugin/start/timedot-vim/t. ~/bin/
chmod +x ~/bin/t.
```

## Usage
- editing file
- reporting with hledger
- working with timedot and ledger-cli

## Contributing

yes, please do!
