First clone this repository in a directory called ~/.dotfiles
git clone https://github.com/kierianrocks/.dotfiles

Then use GNU STOW to create symbolic links
stow ~/dotfiles

Make zsh default shell
chsh -s $(which zsh)

Install oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

Push
First add files to commit
git add {files}

Commit files
git commit -am {message}

push files
git push

Pull
Pull from repo
git pull
