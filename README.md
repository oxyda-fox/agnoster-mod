# Agnoster Mod

![codename](https://img.shields.io/badge/Codename-0xiD4ff0x-orange?style=for-the-badge&logo=python.svg)
[![instagram](https://img.shields.io/badge/Instagram-@risnfd-ff69b4?style=plastic&logo=instagram.svg)](https://instagram.com/risnfd) [![facebook](https://img.shields.io/badge/Facebook-SDrisna-blue?style=plastic&logo=facebook.svg)](https://facebook.com/exmorty99)

# Read First

ID :
>**Ini adalah tema agnoster yang siap**
>**untuk di install pada aplikasi termux.**

EN :
>**This is a agnoster theme that is ready to**
>**be installed on your Termux application.**

# Terms
- You must install curl with this command

```
apt install curl
```

- You must install required fonts with this command
```bash
curl https://github.com/oxyda-fox/agnoster-mod/raw/master/MesloLGS/MesloLGS%20NF%20Regular.ttf > .termux/fonts/MesloLGS/MesloLGS.ttf
```

- You must install oh-my-zsh with this command
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

# How To Install Theme

- First you must have installed zsh/ohmyzsh and change the font to MesloLGS

- Second you copy this command to your shell
```bash
curl https://raw.githubusercontent.com/oxyda-fox/agnoster-mod/master/agnoster-mod.zsh-theme > .oh-my-zsh/themes/moded.zsh-theme
```

- Third open your .zshrc with your text editor, ex nano or vim
`nano .zshrc` or `vim .zshrc`

- Fourth change or rewrite on
`ZSH_THEME="agnoster"` to `ZSH_THEME="moded"`
- Fifth restart your termux app.

# Screenshot

![screenshot](screenshot-1.jpg)

# Troubleshooting

1. **Username/machine name not showing**
If you have an error with your name machine like this
![error](screenshot-2.jpg)
to resolve it, just type
`export USER="yourname"` for example
![resolved](screenshot-3.jpg)

2. **Icon not showing/error**
If you have an error like this
![error](screenshot-4.jpg)
to resolve it, you can install font **MesloLGS**

Modded by RissFadill a.k.a oxyda-fox

![GitHub watchers](https://img.shields.io/github/watchers/oxyda-fox/agnoster-mod?color=orange&label=Watched%20by&style=flat-square)    ![GitHub repo size](https://img.shields.io/github/repo-size/oxyda-fox/agnoster-mod?color=red&style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/oxyda-fox/agnoster-mod?style=flat-square)
