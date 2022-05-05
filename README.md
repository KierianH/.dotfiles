# .dotfiles
Linux dotfiles

First clone this repository in a directory called ~/.dotfiles
/newline
git clone https://github.com/kierianrocks/.dotfiles

Then use GNU STOW to create symbolic links
stow ~/dotfiles

Make zsh default shell
chsh -s $(which zsh)

Install oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
