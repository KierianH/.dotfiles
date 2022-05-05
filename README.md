# .dotfiles
Linux dotfiles

First clone this repository in a directory called ~/.dotfiles
```git clone https://github.com/kierianrocks/.dotfiles```

Then use GNU STOW to create symbolic links <br>
```stow ~/dotfiles```

Make zsh default shell <br>
```chsh -s $(which zsh)```

Install oh-my-zsh <br>
```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```
