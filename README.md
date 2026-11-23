```shell
mkdir -p \
    ~/.config/git/

ln -s \
    "${PWD}/global.gitconfig" \
    ~/.gitconfig

ln -s \
    "${PWD}/global.gitignore" \
    ~/.config/git/ignore

cp \
    "${PWD}/per-machine.gitconfig.example" \
    ~/.config/git/per-machine.gitconfig

#cp \
#    "${PWD}/github-llskyhi.gitconfig.example" \
#    ~/.config/git/github-llskyhi.gitconfig

# don't forget to update the ~/.config/git/per-machine.gitconfig !
```
