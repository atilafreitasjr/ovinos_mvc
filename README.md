####################
## PROJETO FASE 1 ##
####################
# ovinos_mvc

estrutura de projeto em mvc - composer

Para fazer meu primeiro Push vou utilizar um projeto simples 
que é a estrutura de um sistema web baseado no curso da code 
education "PHP com MVC"

Pode ser rodado instanciando um servidor php como o exemplo:
C:\servidorWeb\www\ovinos_MVC\public>php -S 127.0.0.1:8080
#

# Iniciando o Git

Usuario@Usuario-PC MINGW32 ~
$ git config --global user.name "Átila de Freitas"

Usuario@Usuario-PC MINGW32 ~
$ git config --global user.email "atilafreitasjr@gmail.com"

Usuario@Usuario-PC MINGW32 ~
$ git config --global color.ui true

# Criando repositório

Usuario@Usuario-PC MINGW32 /d/aulagit
$ git init

Initialized empty Git repository in D:/aulagit/.git/

# adicinando arquivo

$ git add arquivo.txt

warning: LF will be replaced by CRLF in arquivo.txt.
The file will have its original line endings in your working directory.

Usuario@Usuario-PC MINGW32 /d/aulagit (master)
$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   arquivo.txt

# Commitando arquivos

$ git commit -m "Meu primeiro commit"
[master (root-commit) 8c7f7c1] Meu primeiro commit
warning: LF will be replaced by CRLF in arquivo.txt.
The file will have its original line endings in your working directory.
 1 file changed, 4 insertions(+)
 create mode 100644 arquivo.txt


