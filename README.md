### Instal github CLI

```curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg```

```echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null```

```sudo apt update```

```sudo apt install gh```

### Authenticate with github CLI <br>

```gh auth login```

### Setup
First clone this repository in a home directory <br>
```yadm clone https://github.com/kierianrocks/.dotfiles```

Make zsh default shell <br>
```chsh -s $(which zsh)```

Install oh-my-zsh <br>
```sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```

### Push
Check to see what you've changed <br>
```yadm status```

add files to commit <br>
```yadm add {files}```

Commit files <br>
```yadm commit -am {message}```

push files <br>
```yadm push```

### Pull from repo <br>
```yadm pull```
