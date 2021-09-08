<p align="center">
  <img src="https://img.shields.io/static/v1?label=Learning&message=GIT&color=ffffff&style=for-the-badge&logo=git"/>
  <img src="https://img.shields.io/static/v1?label=Loving&message=GITHUB&color=ffffff&style=for-the-badge&logo=github"/>
</p>

<h1 align="center">ESTE REPOSITÓRIO TEM COMO ÚNICO OBJETIVO SERVIR COMO UM BLOCO DE ANOTAÇÕES PARA MIM MESMO</h1>

# Começo
`git init` = inicia um repositório

# Adicionando modificações ao stage
`git add nome_do_arquivo` = adiciona um arquivo específico ao stage
`git add .` = adiciona todos os arquivos modificados em stage

# Adicionando modificações a linha do tempo
`git commit -m "Mensagem"` = cria um ponto na história do nosso projeto

`git commit -am "Mensagem"` = adiciona todos os arquivos modificados ao stage e cria um ponto na história do projeto com a mensagem entre aspas

# Alterar mensagem do último commit

`git commit --amend -m "Nova mensagem"` = altera a mensagem do último commit apenas

# Adiciona modificações ao último commit

`git add nome_do_arquivo` = faça isso para adicionar as alterações que vocẽ desejava que fossem colocadas no seu último commit 

`git commit --amend --no-edit` = faça isso para adicionar tais alterações ao último commit e não alterar a mensagem dele

# Removendo arquivos do repositório git
`git rm arquivo.txt` = remove arquivo/diretorio 

# Informações sobre o repositório
`git log` = mostra um log de commits // se você não estiver conseguindo sair deste comando mova seu cursor até *exit* e pressione a tecla *q*

`git status` = mostra o estado dos seus arquivos

`git show` = mostra as ultimas alterações realizadas

# Uso das branchs (Ramos)
`git branch nome_branch` = cria nova ramificação do projeto

`git branch` = mostra todas as nossas branchs

`git branch -D nome_branch` = deleta a branch sem dó 

`git merge nome_branch` = mistura a branch citada com a branch que você está

# Uso do checkout
`git checkout n_commit` = te leva de volta ao commit especificado 

`git checkout nome_branch` = te leva até a branch especificada

`git checkout -b nome_branch` = cria uma branch nova e te leva para ela em um mesmo comando

# Mudar a mensagem do último commit 
git commit --amend -m "nova mensagem"

# Adicionar arquivos e modificações ao último commit
git add arquivo

# LÁÁÁÁ NAS NUVENS - GITHUB
`git remote add origin https://url.com` = adiciona um repositório externo

`git remove -v` =  serve para ver seus repositórios remotos

`git push` = empurra seu repositório local para o github // na primeira vez você precisa criar a branch master no github com *git push -u origin master*

`git config credential.helper store` = salva suas credenciais

`git clone https://url.com` = clona um repositório/projeto existente para que você possa trabalhar com ele localmente

`git pull` = puxa o repositório da nuvem para atualizar o repositório local

