---
description: Como enviar mudanças a colaboradores com acesso a repositório remoto
---

# Enviando mudanças (push)

O comando `git commit` efetua as mudanças propostas no repositório local, mas, se estamos trabalhando com o GitHub, como compartilhamos estas mudanças?

A resposta a essa pergunta depende da [forma com que o repositório Git foi criado](inicializacao-init-clone.md), isto é, utilizando `git init` ou `git clone`.

## `git clone`

Este é o caso mais simples, pois quando o repositório utilizado é uma cópia de um repositório existente no GitHub basta executar:

```bash
git push origin master
```

Após o primeiro push deve ser possível enviar as mudanças apenas com:

```bash
git push
```

## `git init`

Caso tenha criado um novo repositório local, utilizando `git init`, deve-se [criar um novo repositório no GitHub](https://docs.github.com/pt/get-started/quickstart/create-a-repo) e inserir:

```bash
git remote add origin <url-para-novo-repositorio>
git branch -M main
git push -u origin main
```

Como vimos anteriormente, depois do primeiro push deve ser possível enviar as mudanças apenas com:

```bash
git push
```
