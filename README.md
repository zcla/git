# git
Anotações para utilização do Git

## Baixando um repositório remoto

`git clone <url>` Não será baixado na pasta atual; será criada uma pasta com o nome do projeto, e o conteúdo estará lá dentro.

## Criando um repositório local

`git init <name>` O repositório não será criado na pasta atual; será criada uma pasta com o nome do projeto, onde ficará o conteúdo.

## Associando arquivos ao repositório local

`git add <file/folder/wildcard>`

> ### Opções desconhecidas
> `... -p`

## Salvando alterações no repositório local

`git commit -m"mensagem"` Cria um "snapshot" do momento.

> ### Opções desconhecidas
> `... -a`

## Copiando o repositório local para o remoto

`git push`

> ### Opções desconhecidas
> `... origin <branch>`

## Buscando alterações no repositório remoto

`git pull`

## Selecionando um branch existente

`git checkout <branch>`

## Criando um branch

`git checkout -b <branch>`

## Juntando branches

`git merge <branch>`

## Buscando o histórico de alterações

`git log --graph --decorate --abbrev-commit --all --pretty=oneline`
