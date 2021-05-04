---
title: Node Version Manager
date: 2021/5/4
description: Como instalar o NVM (Node Version Manager).
tag: Dev-Tools
author: Crisler
---

# Node Version Manager - NVM
## O que é o NVM ?
O **NVM** ou Node Version Manager é um versionador para o [**NodeJS**]() que possibilita que você rode diferentes versões do Node e alterne da maneira que precisar. 
Esta ferramenta é útil que possibilita trabalhar em 
## Como instalar
- Irei ensinar a instalar no Linux, para o Windows você precisará do [**Chocolatey Package Manager**]()
- Você pode utilizar o **curl** e o **wget**
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
- Depois de instalado você tera que abrir no editor o arquivo **.bashrc** ou **.zshrc** e colocar essa configuração:
```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
## Caso queira saber mais veja o repositório do [NVM no Github](https://github.com/nvm-sh/nvm)