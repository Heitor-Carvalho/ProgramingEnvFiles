# Programming environment file

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


