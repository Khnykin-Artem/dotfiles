<h1>DOTFILES</h1>
<h2>WORK ENVIRONMENT</h2>
<h3>Install utilities</h3>
<code>
sudo eopkg install xclip xsel <br>
sudo eopkg install neofetch fastfetch ifconfig unzip
</code>
<h3>Install environments</h3>
<code>
sudo eopkg install -c system.devel <br>
sudo eopkg install ruby-devel <br>
sudo eopkg install sqlite3-devel <br>
sudo eopkg install nodejs
</code>
<h3>Install package managers</h3>
<code>
sudo eopkg install gem snapd
</code>
<h2>ZSH</h2>
<h3>Install zsh</h3>
<code>sudo eopkg install zsh</code>
<h3>Install Oh My Zsh</h3>
<code>sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"</code>
<h3>Install Powerlevel10k</h3>
<code>git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k</code>
<h3>Install plugins</h3>
<code>git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting <br>
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions <br>
git clone https://github.com/MichaelAquilina/zsh-you-should-use.git $ZSH_CUSTOM/plugins/you-should-use <br>
git clone https://github.com/agkozak/zsh-z ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z <br>
git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search <br>
sudo eopkg install fzf <br>
sudo gem install colorls</code>
<h3>Clone config files</h3>
<code>cd ~ <br>
git clone https://github.com/Khnykin-Artem/dotfiles.git <br>
cd dotfiles <br>
sudo mv ~/dotfiles/.zshrc ~/ <br>
sudo mv ~/dotfiles/.bashrc ~/ <br>
sudo mv ~/dotfiles/.p10k.zsh ~/ <br>
sudo mv ~/dotfiles/usr/share/fonts/* /usr/share/fonts/</code>
<h3>ZSH final</h3>
<code>sudo source ~/.zshrc</code>
