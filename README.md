# Comandos_Git
Fluxo do GITHUB


# Configuração global


git config --list

git config --global user.name "ricardovieiradesouza"

git config --global user.email "ricardosouza.suporte@outlook.com"



# Para adicionar um arquivo deve se inicar o projeto com comando 

git init

# Arquivos criado mas em Untracked files:

#Para adicionar basta realizar o comando:

git add <nome do arquivo>

git status
  
  
#unstage - Adicionado para ser comitado porém sem comite 
#Untracked - Arquivo não adionado para ser comitado

  
#Boa praticas do git deve ser adicionado somente o arquivo que houve alteração.

#Agora o arquivo esta pronto para ser commitado
  
# Após alteração no arquivo deve ser comitado com o seguinte comando:

git commit -m "Adicionando segundo linha"

# Comando para verificar as alteração 

git diff

iff --git a/README.md b/README.md
index 22f8ac4..7164e16 100644
--- a/README.md
+++ b/README.md
@@ -1 +1 @@
-Arquivo inical
+Arquivo terceiro comentatioiff --git a/README.md b/README.md

  
  
# Vizualizar a diferença entre os arquivos depois do commit

git log 

# Ira aparecer todos os logs e poderá pegar um commit 

#Exemplo

 git log

  
  
  
  
commit ae52403e14ac0e531eebd0838e369a3ed7fd70d5 (HEAD -> master)
  
Author: ricardovieiradesouza <ricardosouza.suporte@outlook.com>
  
Date:   Sat Aug 14 01:35:41 2021 +0530

    adionando quarta linha
  

commit d3bdddddf3f521a91cf89656477476c9facae18a
  
Author: ricardovieiradesouza <ricardosouza.suporte@outlook.com>
  
Date:   Sat Aug 14 00:47:19 2021 +0530
  

    Adicionando segundo linha
  
  
  
====================================================================

# Logo depois basta pegar o numero do commit e pesquisar com comando:


git show <numero do commit>

  
############   FLUXO DO GIT #####################

git status
  
#alterar os arquivos
  
git add <arquivo>
  
git diff
  
git commit -m "a alteração que foi realiza"
  
git log
  
git show <número do commit>
  
git log --decorate
  
git log --decorate --oneline
  
git shortlog


##############################################

# Verificar os logs mais detalhadamente 

git log --decorate 

git log --decorate --oneline

git log --decorate --oneline --graph

git shortlog

git shortlog -sn   #quantidade de commit


##############################################





