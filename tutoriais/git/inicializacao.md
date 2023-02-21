---
description: Criando novos repositórios e copiando repositórios existentes
---

# Inicialização

Um projeto com versionamento em Git pode ser iniciado de duas maneiras: a partir da criação de um novo repositório ou copiando um repositório já existente, seja este local ou remoto.

## Criando novo repositório

Para criar um repositório Git basta abrir a pasta desejada e inserir o comando:

```bash
git init
```

{% hint style="info" %}
Ao abrir um terminal certifique-se de que os comandos do Git estão sendo executados na pasta correta
{% endhint %}

## Copiando repositórios

Para copiar um repositório local, abra a pasta desejada e insira:

```bash
git clone /caminho/do/repositorio
```

Caso o repositório esteja em um servidor remoto, como é o caso do GitHub, podemos utilizar o mesmo comando, colocando a URL do repositório no lugar do caminho para o arquivo:

```bash
git clone https://github.com/optimumconsultoria/optimumconsultoria.github.io
```

## Conclusão

Vimos que os comandos `git init` e `git clone` são utilizados para iniciar o fluxo de trabalho em Git. Caso o repositório esteja sendo criado pela primeira vez utilizamos `git init`, caso este já exista e desejemos trabalhar com uma versão local utilizamos `git clone`.
