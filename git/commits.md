# Commits

Um commit representa um ponto da história do projeto.

Sempre que uma alteração relevante for concluída, recomenda-se registrar um commit com uma mensagem clara e objetiva.

## Estrutura recomendada

Uma boa mensagem de commit deve responder:

> O que foi alterado?

Exemplos:

```bash
git commit -m "Adiciona documentação da tabela tb_material"
```

```bash
git commit -m "Atualiza dicionário de situação do material"
```

```bash
git commit -m "Corrige erro na consulta SQL de infrações contra idosos"
```

## Exemplos de boas mensagens

### Documentação

```bash
git commit -m "Adiciona README do projeto"
```

```bash
git commit -m "Atualiza guia de utilização da Git Bash"
```

### Metadados

```bash
git commit -m "Adiciona estrutura da tabela tb_envolvido_ocorrencia"
```

```bash
git commit -m "Inclui dicionário do campo situacao_codigo"
```

### Scripts

```bash
git commit -m "Cria script para geração de catálogo HTML"
```

```bash
git commit -m "Otimiza consulta de materiais apreendidos"
```

### Correções

```bash
git commit -m "Corrige descrição duplicada do código 1300"
```

```bash
git commit -m "Ajusta caminho de leitura dos arquivos CSV"
```

## Evitar

Mensagens genéricas dificultam a compreensão do histórico.

Exemplos que devem ser evitados:

```bash
git commit -m "ajustes"
```

```bash
git commit -m "alteração"
```

```bash
git commit -m "teste"
```

```bash
git commit -m "corrigido"
```

## Dica

Ao ler a mensagem de commit daqui a seis meses, ela ainda deve explicar claramente o que foi realizado.
