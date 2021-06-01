# Git-Commands
This repository has a description of some git commands.

git init - inicializa um repositorio.

git status - verifica as modificações.

git add ["nome-do-arquivo" ou "."] - inserindo o nome do arquivo em especifico ou adicionando um ponto para commitar todas as alterações realizada.

git commit -m "descrição-do-commit" - Relaciona as suas alterações adicionadas pelo comando "git add" e adiciona uma descrição ao commit.

git push - Envia o commit, salvando em seu software de versionamento, como github ou bitbucket...

git log - Exibe os commits realizados de forma completa.

git log --oneline - Exibe os commits relizado de forma resuimida / Historico de commits.

[ESQ] e depois "q!" - sai do editor VIM.

Retornar ao estado anterior das alterações
--
git clear -df

git checkout -- .

Desfazendo o ultimo commit, mas permanecendo com as alterações no arquivo.
--
$ git reset --soft HEAD~1

Desfazendo o ultimo commit com as alterações no arquivo.
--
$ git reset --hard HEAD~1

Abrir versões anteriores.
--
git checkout [codigo-do-commit]

Associando um repositorio local ao remoto
--
git remote add origin [url-do-repositorio]
git remote set-url origin [url-do-repositorio]
