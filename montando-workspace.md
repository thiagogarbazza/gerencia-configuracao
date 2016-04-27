# Ambiente desenvolvimento #

## Sistema Operacional##

Instalar os seguintes programas da central
1. Chromium Web Browser
2. Main Menu (Alacart)

## Controle de versão ##

### GIT ###

```bash
$ sudo apt-get update
$ sudo apt-get install git
```

```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "your.email@domain.com"
```

[Tutorial provido pelo GitHub][git-ref]

### SSH keygen ###

```bash
$ ssh-keygen -t rsa -b 4096 -C "your.email@domain.com"
$ ssh-add ~/.ssh/id_rsa
```


[Tutorial provido pelo GitHub][ssh-keygen]


### File Compare ###

```bash
$ sudo apt-get install meld
```

## Linguagens ##

### Java ###

```bash
$ sudo apt-get install python-software-properties
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get update
$ sudo apt-get install oracle-java8-installer
```

#### JDK ####

#### Maven ####

```bash
$ sudo apt-get install maven
```

[Tutorial][maven]

### Node ###

```bash
$ sudo apt-get install nodejs
```

[Tutorial][nodejs-ref]


#### NPM ####

```bash
$ sudo apt-get install npm
```

#### Bower ####

```bash
$ npm install -g bower
```

[Tutorial][bower-ref]

### Gulp ###

```bash
$ npm install -g gulp-cli
```

### Stylus-lang ###

```bash
$ npm install -g stylus
```

## IDE's ##

### Sublime Text 3 ###

```bash
$ sudo add-apt-repository ppa:webupd8team/sublime-text-3
$ sudo apt-get update
$ sudo apt-get install sublime-text-installer
```

Instalar Package Control [veja aqui][sublime-package-control]


### Intellij Idea ###

Para [Download](https://www.jetbrains.com/idea/ "Clique aqui para realizar o Download da IDE")

Para descompactar Faça os seguintes passos:
 1. Abra o Terminal e digite -> $ sudo nautilus
 2. Descompacto o arquivo em /opt
 3. Abra o Main menu e adicione um item de menu para o Intellij Idea
 4. Abra a IDE e 






[git-ref]: https://help.github.com/articles/set-up-git/  "Referência de como instalar o GIT"
[ssh-keygen]: https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/ "Referência de como gerar a chave SSH" 
[sublime-package-control]: https://packagecontrol.io/installation#st3 "Referência de como instalar o Package Control do Sublime Text"


[java-jre]: https://www.digitalocean.com/community/tutorials/como-instalar-o-java-no-ubuntu-com-apt-get-pt "Referência instalação Java"
[maven]: http://www.mkyong.com/maven/how-to-install-maven-in-ubuntu/ "Referência instalação Maven"

[nodejs-ref]: https://www.digitalocean.com/community/tutorials/como-instalar-o-node-js-em-um-servidor-ubuntu-14-04-pt "Referência instalação Nodejs"
[bower-ref]: http://bower.io/#install-bower
[gulp-ref]: https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md

[intellij-idea-keygen]: http://us.idea.lanyus.com/
