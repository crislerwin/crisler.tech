---
title: Node Version Manager ⌨️
date: 2021/5/4
description: NVM (Node Version Manager).
tag: Dev-Tools
author: Crisler
---
<>
<iframe width="480" height="300" src="https://www.youtube.com/embed/Si6L8gwSc8Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</>
# Node Version Manager - NVM
## O que é o NVM ?
O **NVM** ou Node Version Manager é um versionador para o [**NodeJS**]() que possibilita que você rode diferentes versões do Node e alterne da maneira que precisar. 
Esta ferramenta é útil que possibilita trabalhar em aplicações utilizando diferentes versões do Node sem precisar ter que ficar instalando todas as vezes. Esta ferramenta permite que você alterne de versões de forma simples e inclusive te permite nomear versões:
```
 nvm alias default v14
```
## Como instalar
- No Linux você pode utilizar o **curl** e o **wget**
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
- No Windows você precisará instalar o [**Chocolatey**](https://chocolatey.org/install)
No Powershell ou CMD como administrador após ter instalado o **choco**
```
    choco install nvm
```

Caso queira saber mais veja o repositório do [NVM no Github](https://github.com/nvm-sh/nvm)

 Feito com ❤️ por Crisler Wintler