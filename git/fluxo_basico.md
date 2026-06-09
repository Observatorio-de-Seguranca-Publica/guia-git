# Fluxo Básico de Utilização do Git

Após clonar um repositório do GitHub, o trabalho com Git normalmente segue um fluxo simples e repetitivo. Compreender esse ciclo é mais importante do que memorizar dezenas de comandos.

O fluxo adotado segue os passos abaixo:

1. Atualizar o repositório local
2. Realizar alterações
3. Verificar as mudanças realizadas
4. Adicionar alterações ao Git
5. Criar um commit
6. Enviar alterações para o GitHub

---

## 1. Atualizar o repositório local

Antes de iniciar qualquer atividade, recomenda-se garantir que a cópia local esteja atualizada.

```bash
git fetch
git pull origin main
```

---

## 2. Realizar alterações

Neste momento podem ser criados, removidos ou modificados arquivos utilizando o VSCode.

---

## 3. Verificar as alterações realizadas

O comando abaixo permite verificar quais arquivos foram modificados:

```bash
git status
```

Exemplo de retorno:

```text
On branch main

Changes not staged for commit:

modified: README.md
modified: tb_material.md
```

---

## 4. Adicionar alterações ao Git

Após concluir as alterações desejadas, é necessário informar ao Git quais arquivos deverão fazer parte do próximo commit.

Adicionar um arquivo específico:

```bash
git add README.md
```

Adicionar todos os arquivos alterados:

```bash
git add .
```

O comando `git status` pode ser utilizado novamente para verificar se os arquivos foram adicionados corretamente.

---

## 5. Criar um commit

O commit registra um ponto da história do projeto.

Exemplo:

```bash
git commit -m "Atualiza documentação da tabela tb_material"
```

Uma boa mensagem de commit deve descrever de forma objetiva o que foi alterado.

Mais exemplos podem ser encontrados no documento de commits deste guia.

---

## 6. Enviar alterações para o GitHub

Após criar o commit, as alterações ainda estão apenas na máquina local.

Para enviá-las ao GitHub:

```bash
git push origin main
```

---

# Fluxo Resumido

O ciclo mais comum de utilização do Git pode ser representado da seguinte forma:

```bash
git pull origin main
git status
git add .
git commit -m "Descrição da alteração"
git push origin main
```

---

# Comandos Auxiliares

## Inicializar Git em uma pasta

Transforma uma pasta comum em um repositório Git.

```bash
git init
```

---

## Clonar um repositório

Cria uma cópia local de um repositório existente.

```bash
git clone [link_repositorio]
```

Exemplo:

```bash
git clone https://github.com/Observatorio-de-Seguranca-Publica/guia-git.git
```

---

## Consultar histórico de commits

Permite visualizar os commits realizados no projeto.

```bash
git log
```

---

## Restaurar alterações de um arquivo

Descarta alterações ainda não commitadas.

```bash
git restore nome_arquivo
```

Exemplo:

```bash
git restore README.md
```

---

# Observação

À medida que os projetos evoluem, o fluxo de trabalho pode incluir recursos adicionais como:

* Branches
* Issues
* Pull Requests

Esses temas são abordados em documentos específicos neste repositório.
