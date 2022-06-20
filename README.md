# system-setting

## zsh, git, vim, curl, gcc, g++, nvidia(if needed) 

### zsh

- sudo apt install zsh
- chsh -s /bin/zsh
- wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh
- zsh-syntax-highlighting
	- git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

	- plugins=( zsh-syntax-highlighting)
- zsh-autosuggestions
	- git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
	- plugins=(zsh-syntax-autosuggestions)
- autojump
	- sudo apt install autojump
	- [[ -s ~/.autojump/etc/profile.d/autojump.sh ]] && . ~/.autojump/etc/profile.d/autojump.sh 写入.zshrc
