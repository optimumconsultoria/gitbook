---
description: Propondo e fazendo mudanças
---

# Add e Commit

{% hint style="info" %}
Certifique-se que está executando estes comandos com a pasta correta aberta no terminal
{% endhint %}

## `git status`

Uma vez iniciado um fluxo de trabalho em Git, todas as mudanças realizadas nos arquivos são registradas e podem ser vistas utilizando o comando `git status`. O `git status` lista o nome de todos os arquivos com mudanças, que podem ser propostas por meio do comando `git add`.

## `git add`

Para propor mudanças a um arquivo específico utilize:

```bash
git add <nome-do-arquivo>
```

Para propor mudanças a todos os arquivos listados pelo `git status` utilizamos o seguinte comando:

```bash
git add *
```

## `git commit`

Após todas as propostas de mudanças serem adicionadas com `git add`, utiliza-se o comando `git commit` para efetuar essas mudanças da seguinte maneira:

```bash
git commit -m "Mensagem do commit"
```

Cada commit é obrigatoriamente acompanhado de uma breve mensagem que ajuda a identificar quais mudanças estão sendo realizadas.&#x20;

Após efetuar o commit, as mudanças são realizadas no repositório local e os arquivos deixam de aparecer no `git status`.
