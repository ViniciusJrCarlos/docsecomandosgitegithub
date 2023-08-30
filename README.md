## Resumos e comandos IDE'S GIT e GITHUB

Repositório para armazenar resumos sobre git e github do curso e versionamento de código com git e github da [Digital Innovation one](https://www.dio.me/).

## Documentação 

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## Resumo das Aulas

| Aulas | Resumos |
| ------| ------------|
| Aula 01 | [Resumo]() |
| Aula 02 | [Resumo]() |

```

1 - COMANDO GIT INIT NO TERMINAL DO VSCODE NO BASH
git init

==================================================================

2 - COMANDO PARA ALTERAR PARA BRANCH MAIN

git branch -M "main"
===================================================================
3 - ENVIA SOMENTE O ARQUIVO .MD PARA O GIT STADING  AGUARDANDO O PUSH PARA O REPOSITORIO REMOTO

git add README.md 

4 - ENVIA TODOS ARQUIVOS ALTERADOS PARA O GIT STADING, AGUARDANDO O PUSH PARA O REPOSITORIO REMOTO
git add .

git add *

=================================================================

5 - GIT PULL 

BAIXA AS ALTERAÇOES DO REPOSITORIO REMOTO PARA SEU REPOSITORIO LOCAL

=================================================================

6 - COMANDO PARA VER OS LOGS DOS COMMITS JÁ FEITOS 

git log

================================================================

7 -  COMANDO QUE ALTERA O NOME DA MENSAGEM DE UM COMMIT ENVIADO
git commit --amend -m "alterando nome do comiit que foi enviado"

================================================================

8 - COMANDO PARA VER TODAS AS BRANCHS JÁ FEITAS
git branch

================================================================
9 - COMANDO PARA CRIAR UMA NOVA BRANCH
git checkout -b #nomedanovabranch

10 - COMANDO PARA MUDAR DE BRANCH 
git checkout #nomedaBranch que deseja acessar

===============================================================
11 - COMANDO PARA VOLTAR PARA BRANCH QUE VOCE DESEJA
git checkout main ou outra branch

===============================================================
12 - COMANDO PARA VER ULTIMO COMMIT DE TODAS BRANCHS

git branch -v

===============================================================

13 - COMANDO PARA MESCLAR AS BRANCHS E DESEJAR AMBAS NO MESMO STATUS

git merge #nomedabranch > esse comando irá mesclar e atualizar para branch que estiver 
mais atual.

===============================================================

14 - COMANDO PARA EXCLUIR UMA BRANCH QUE NAO VAI SER MAIS USADA

git branch -d #nomedabranch a ser excluida.

===============================================================

15 - COMANDO PARA CORRIGIR ALGUNS CONFLITOS DE MERGE ENTRE ARQUIVOS, QUANDO ALTERA ALGUMA INFORMACAO DO GIT REMOTO
E DESEJA MANTER ATUALIZADO NO GIT LOCAL

git fetch origin main

=================================================================

16 - COMANDO USADO PARA VER AS DIFERENCAS ENTRE COMMITS QUE JA FORAM FEITOS EM BRANCHS
git diff main origin/main

=================================================================

17 - COMANDO PARA MESCLAR AS INFORMACOES QUE FORAM ATUALIZADAS DA BRANCH REMOTA PARA BRANCH LOCAL 
git merge origin/main

================================================================

18 - COMANDO PARA CLONAR APENAS UMA BRANCH QUE FOI FEITA NO GIT REMOTO PARA O GIT LOCAL
git clone https://github.com/#seureposito.git --branch #nomebranch --single-branch

=================================================================

COMANDO PARA ARQUIVAR ALGUMA ALTERACAO QUE FOI FEITA NUMA BRANCH POREM NAO APARECER NA OUTRA BRANCH
git stash list

git stash pop (trazer as alteracoes e excluir as alteracoes mais recentes da pilha )

git stach apply (mantem a alteração na lista para usar posterior)

================================================================

INFORMAÇÃO SOBRE FORK

quando voce clona um projeto de terceiro 

- realizar o fork
- criar uma pasta no seu git com outro nome
- realizar o clone para sua maquina local com vscode
- realizar o git pull para atualizar tudo
- realizar alguma alteracao no readme e realizar os comandos de git add . 

================================================================

INFORMAÇÃO SOBRE COMMIT 


echo "### NOMEDOPROJETO" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/#NOMEDOPROJETOGIT
git push -u origin main

=============================================================

```




## Referencias 

- [Digital Innovation One]().