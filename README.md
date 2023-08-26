# Bootcamp Santander | Fullstack → Angular + Java

Projetos realizados ao longo do Bootcamp na plataforma [Digital Innovation One](https://www.dio.me/)

## Documentação

- [Documentação git](https://git-scm.com/docs/git/pt_BR)

## Sobre as aulas

### git e GitHub:
O que é, como funciona e principais comandos.
[parametro opcional ou editavel]

**.gitignore -** arquivo para indicar ao git arquivos e diretorios que devem ser ignorados

**.gitkeep -** arquivo para que o git reconheça diretorios vazios

| Comando                                              | o que faz?                                                                                           |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| git init                                             | inicializa um repositorio local                                                                      |
| git remote add [origin] URL                          | conecta o repositorio local ao remoto. origin é o nome do servidor remoto, pode ser alterado        |
| git clone URL [nome do diretorio]                    | clona o repositorio remoto|
| git clone URL --branch [nome-branch] --single-branch |clona somente esta branch|
| git status                                           | exibe o status atual da branch, arquivos alterados a serem commitados e salvos no repositorio remoto |
| git add [nome do arquivo]                            | adiciona o arquivo ao proximo commit a ser salvo                                                     |
| git add .                                            | adiciona todos os arquivos alterados ao commit                                                       |
| git log                                              | resumo dos commits, apresenta hash do commit, autor data e título                                   |
|git restore [arquivo]|restaura o arquivo para a última versão salva, último commit local|
|git commit --amend -m "Nova mensagem"|altera a mensagem do último commit local|
|git reflog|historico de commit e as alterações feitas neles|
|git restore [arquivo]|restaura o arquivo ao ultimo estado|
|git restore --staged [arquivo]|retira o arquivo da arvore de preparo e mantem o seu estado|
|git push|envia o commit para o repositorio remoto|
|git push -u [origin] [branch]| envia e defini e branch como a padrão para os proximos commits|
|git pull|atualiza o repositorio local com as atualizações do remoto|
|git checkout -b [branch]|cria e troca para essa nova branch|
|git checkout [branch]|troca de branch|
|git branch -d [branch]|deleta a branch|

