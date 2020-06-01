# Programming environment file

This repo contains all my environment configuration files used to development.

### Setting up tmux file
 * Download the tmux.conf file and move to .tmux.conf
 * Clone the plugin manager with the command with the command:

 ```
 git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
 ```

 * Enter tmux and run the following command to download the other plugins

 ```
 Prefix + I
 ```

 * Finally install the urlview to enable the plugin tmux-urlview following command:

 ```
 apt-get install urlview
 ```

### Setting up gitconfig file
 * Download the gitconfig file and move to .gitconfig
 * Change the name and email

### Setting up bash related files
 * Download the files bash_aliases and bash_extends and copy to home adding the . at begining of the file name
 * Adding "source .bash_extends" to .bashrc file
 * Run the commando to enable the up command
```
curl --create-dirs -o ~/.config/up/up.sh https://raw.githubusercontent.com/shannonmoeller/up/master/up.sh
```

### Setting up vim related files
 * Download the files vimrc and cscope_maps.vim
 * Move the vimrc to ~/.vimrc
 * Move the cscope_maps.vim to ~/.vim/
 * Open vim and install all the plugins with the command
```
:PluginInstall
```
 * To full enable the tags generate file run:
```
 sudo apt-get install exuberant-ctags
```
 * To full enable you complete me run:
```
 cd ~/.vim/bundle/YouCompleteMe
 python3 install.py --all
```
 * To check if the copy to clipboard from vim is work run and check if return 1
```
 :echo has('clipboard') 
```
* If not try
```
 install the vim-gtk or vim-gtk3 package
```
