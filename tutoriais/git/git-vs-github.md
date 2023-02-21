---
description: Afinal, qual é a diferença?
cover: ../../.gitbook/assets/git-and-github.png
coverY: 0
---

# Git vs GitHub

{% hint style="info" %}
Apesar do nome, as funcionalidades e propósitos do Git e do GitHub são diferentes, porém complementares
{% endhint %}

## GitHub

O GitHub é o maior site de hospedagem de código fonte do planeta. Sua importância para o desenvolvimento de software é tamanha que a Microsoft comprou a plataforma em 2018 por US$ 7,5 bilhões.

Em geral, o site é utilizado como servidor para armazenar e compartilhar as mudanças realizadas nos códigos. A integração com o Git se dá por meio de **repositórios**, que nada mais são do que pastas com suporte ao versionamento de códigos, que podem ser baixadas e enviadas ao GitHub, sendo disponibilizadas publicamente ou apenas com a equipe envolvida no trabalho.

Apesar de ser a maior plataforma que oferece esse serviço de hospedagem, o GitHub não é a única, e nem é imprescíndivel para a utilização do Git. Alternativas como o GitLab oferecem esse mesmo tipo de serviço com planos pagos que oferecem mais opções de controle sobre os repositórios. Além disso, é possível trabalhar com o Git apenas na máquina local, sem jamais realizar o upload de suas informações para um servidor na web, ou ainda utilizar um servidor interno da empresa para obter ainda mais controle sobre os repositórios.

{% hint style="info" %}
Isso significa que não é necessária conexão com a internet para a utilização do Git, salvo o caso de uso de comandos que comunicam-se com o servidor do GitHub (remoto), conforme veremos posteriormente (exemplos: `git clone`,`git push` e `git pull`)
{% endhint %}

## Resumo

Agora sabemos que o Git é um software, que é instalado em seu computador, e pode ser utilizado para diversos propósitos que envolvam o controle de versões de códigos. O GitHub é um site que facilita o compartilhamento dessas alterações oferencendo, entre seus serviços, a possibilidade de hospedar repositórios públicos ou privados na web, os quais tornam-se acessíveis para quaisquer pessoas interessadas de qualquer lugar do planeta.
