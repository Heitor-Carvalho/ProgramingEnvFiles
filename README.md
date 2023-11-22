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
 * Add "source .bash_extends" to .bashrc file

### Setting ssh files
 * Copy the ssh file to ~/.ssh

### Setting sysenv files
 * Add the changes in sysctl.conf to the file /etc/sysctl.conf

### Setting up vim related files
 * Set up Vundle: git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
 * Download the files vimrc and cscope_maps.vim
 * Move the vimrc to ~/.vimrc
 * Move the cscope_maps.vim to ~/.vim/
 * Open vim and install all the plugins with the command
 * Check if vim-gtk is installed
 * Check if copy to clipboard is enabled, e.g. :echo has('clipboard')
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

### Setting up cool tools
 * Install zoxide: https://github.com/ajeetdsouza/zoxide
 * Install tldr: apt install tldr
 * Update tldr with: tldr -u
