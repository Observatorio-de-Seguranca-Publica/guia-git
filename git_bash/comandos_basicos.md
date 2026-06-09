# Listando os principais comandos utilizados na Git Bash

Para a utilização do terminal de comando, é necessária a memorização de diversos comandos para a plena utilização de todas as funcionalidades. Entretanto, sobretudo para usuários iniciantes, o autodesenvolvimento na ferramenta é extremamente complicado sem o auxílio de uma "cola", que ajuda a destravar a utilização do terminal durante as primeiras utilizações.
Obviamente, o conhecimento e fluidez na utilização da Git Bash só ocorre com o tempo e a prática, porém, uma lista com os comandos básicos pode ser um bom "empurrãozinho" para ajudar a tornar esse momento menos espinhoso.

Antes de colocar a lista dos principais comandos, é importante ressaltar que a utilização do "--help" na frente de qualquer comando faz com que o Git Bash dê uma ajuda explicando a sintaxe e os retornos daquele comando.

Lista principais comandos:

## Utilizando a navegação dentro do próprio PC via GitBash
* pwd (“Print Working Directory”) -> Mostra em qual diretório está trabalhando no momento:
```bash
$ pwd
c/Users/Downloads/code/observatorio/guia-git
```
* ls -> Lista o conteúdo da diretório que está trabalhando no momento:
```bash
$ ls
bash-basico.md  git-basico.md  README.md
```
* ls -la -> Lista o conteúdo da diretório que está trabalhando no momento, inclusive o que está oculto. Comando importante para verificar, por exemplo, se o “.git” está ativo naquele diretório:
```bash
$ ls -la
drwxr-xr-x 1 x15501492 1049089    0 Feb  2 16:19 ./
drwxr-xr-x 1 x15501492 1049089    0 Apr  9 12:05 ../
drwxr-xr-x 1 x15501492 1049089    0 Jun  9 11:31 .git/
-rw-r--r-- 1 x15501492 1049089 2040 Jun  9 12:03 bash-basico.md
-rw-r--r-- 1 x15501492 1049089 2339 Feb  2 16:19 git-basico.md
-rw-r--r-- 1 x15501492 1049089  884 Jun  9 11:52 README.md
```
* cd [nome_diretorio] (“change directory”) -> Altera o diretório em que está trabalhando para a pasta indicado no [nome_pasta].
* touch [nome_arquivo.extensao_arquivo] -> Cria um arquivo, importante lembrar da extensão (.py; .sql; .md):
```bash
$ touch teste.md
```
* rm -rf  [nome_documento] -> Remove arquivo/diretório/pasta permanentemente:
```bash
$ rm -rf teste.md
```
⚠ Atenção: rm -rf remove arquivos e diretórios permanentemente. Utilize com cuidado.

* mkdir [nome_pasta] -> Cria uma pasta:
```bash
$ mkdir aprendendo_git
```