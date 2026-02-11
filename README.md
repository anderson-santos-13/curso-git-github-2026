# Curso TMW Git & Github 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no nosso Youtube. É gratis!


## Fluxo de trabalho Git local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add .
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto proprio ou da sua empresa)

01. git clone <endereço do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add "arquivos"
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -d <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

01. Fork do projeto para seu próprio GitHub
02. git clone <endereço_do_projeto>
03. git checkout -b <nova_branch>
04. alterações de arquivos
05. git status
06. git add "arquivos"
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abrir Pull request no GitHub para main
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -d <nova_branch>

----------------