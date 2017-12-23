## Links
```
cd %userprofile%
mklink _vimrc c:\dotfiles-windows\home\_vimrc

cd %appdata%\Code\User
mklink settings.json c:\dotfiles-windows\roaming\Code\User\settings.json

```

```
cd %appdata%
mklink /D StrokesPlus c:\dotfiles-windows\roaming\StrokesPlus
```

## Vundle
```
cd %USERPROFILE%
git clone https://github.com/VundleVim/Vundle.vim.git vimfiles/bundle/Vundle.vim
```

```
:bundleinstall
```


## Spacemacs
cd %userprofile%
mklink .spacemacs c:\dotfiles-windows\home\.spacemacs

