Comandos basicos

configuracao inicial

git config --global user.name "Anderson"
git config --global user.email "andersonmacedo1782@hotmail.com"
git config --global core.editor code .
git config --list

git init //iniciar repositorio "untracked"
git status //mostra arquivos modificados 
git add nome arquivo //adiciona ao git "stage area"
git rm nome arquivo //remove ao git "stage area"
git commit -m "msg" //adiciona ao "stage repository"
git log //mostra informacoes
git log --decorate //mostra informacoes e qual branch
git log --author "nome pessoa"
git shortlog //mostra resumo qtos autores e quais msg commits
git shortlog -sn //mostra qtde commits e nome pessoa
git log --graph //mostra forma grafica os commits
git show e041228f1bd658006c4258a21c5e27b1ead2e84e //mostra detalhes da rash
git diff //mostra as mudancas antes de adiconar ao stage area fazer commit
git diff --name-only // mostra apenas nomes arquivos antes de adiconar ao stage area fazer commit
git checkout nome arquivo //volta para estado antes de ser modificado (obs. usar git diff antes)
git reset HEAD nome arquivo //volta arquivo do estage area apos add.
