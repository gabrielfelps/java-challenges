🇺🇸 [Read in English](README.md)

# Reposítorio de exercícios: Java

Terminei o módulo básico-intermediário do curso Java10x, do Horácio Fiasco, e fiquei com uma sensação incômoda. Eu entendia cada aula. Acompanhava o código, concordava com a explicação, anotava tudo. E mesmo assim não tinha certeza de que conseguiria abrir um arquivo em branco e resolver um problema sozinho.

Assistir alguém resolver um problema é muito diferente de resolver. Pense em ler sobre como andar de bicicleta: você sai da leitura sabendo os nomes das peças, mas continua caindo no primeiro metro.

Este repositório é minha tentativa de parar de cair. São dez desafios, do console mais simples até um sistema de biblioteca universitária, todos em Java puro, sem framework e sem biblioteca externa.

## Como isso funciona

Os enunciados dizem **o que** precisa acontecer, nunca **como**. Nenhum deles manda criar uma classe abstrata ou usar uma pilha. Decidir isso é justamente o exercício. Algumas restrições empurram a solução numa direção (no Jogo da Velha, por exemplo, é proibido escrever na mão as oito combinações vencedoras, e dá muita vontade de escrever), mas a decisão final é sempre minha.

Não existe solução pronta. Quando travo, peço dica, e as dicas vão das mais sutis às mais diretas. Só vejo uma solução completa se eu pedir de forma explícita, e a ideia é pedir o mínimo possível.

Os exercícios foram elaborados com a ajuda do Claude (Anthropic), a partir da lista de conteúdos do módulo. Ele também avalia as minhas soluções: aponta o que está certo, o que está errado e por quê, sem reescrever o meu código. O código de cada solução é meu.

## Os três níveis

**Nível 1: Consolidação (exercícios 1 a 4).** Fundamentos combinados. Menus, laços, arrays, matrizes e as primeiras classes, já com a exigência de que o código fique organizado.

**Nível 2: Aplicação integrada (exercícios 5 a 7).** Aqui o problema deixa de caber numa classe só. Hierarquias, interfaces, enums, generics e records entram para valer, e a pergunta muda de "como faço isso funcionar?" para "como estruturo isso para que aguente mudanças?".

**Nível 3: Desafios complexos (exercícios 8 a 10).** Estruturas de dados escolhidas com justificativa, relações entre vários objetos e um projeto final que junta o módulo inteiro.

A dificuldade não vem de escrever mais código. Vem de ter mais decisões para tomar.

## Progresso

| # | Desafio | Nível | Status |
|---|---------|-------|--------|
| 1 | Terminal de Caixa Eletrônico | 1 | ⬜ |
| 2 | Analisador de Notas da Turma | 1 | ⬜ |
| 3 | Jogo da Velha no Console | 1 | ⬜ |
| 4 | Estoque do Mercadinho | 1 | ⬜ |
| 5 | Locadora de Veículos | 2 | ⬜ |
| 6 | Checkout de uma Loja Virtual | 2 | ⬜ |
| 7 | Catálogo de Filmes e Séries | 2 | ⬜ |
| 8 | Editor de Texto com Desfazer e Refazer | 3 | ⬜ |
| 9 | Central de Atendimento de uma Clínica | 3 | ⬜ |
| 10 | Biblioteca Universitária | 3 | ⬜ |

Cada exercício concluído ganha sua própria pasta, com enunciado, minha solução e as notas da avaliação.

## O que está sendo praticado

Tipos primitivos e de referência, condicionais, laços, `Scanner`, `switch`, operador ternário, arrays e matrizes. Depois, classes, objetos, construtores e sobrecarga, encapsulamento, herança, classes abstratas, interfaces, polimorfismo, `final`, enums, generics, records e as coleções `List`, `ArrayList`, `LinkedList`, `Stack` e `Queue`.

Todos esses tópicos aparecem em pelo menos um desafio, e nenhum aparece sozinho.

## Rodando o código

Você precisa do Java 16 ou superior (por causa dos records). As instruções de cada exercício ficam no README da própria pasta.

## Uma ressalva

Não sei se dez exercícios bastam para consolidar um módulo inteiro. Provavelmente não. Mas prefiro dez problemas em que errei, entendi o erro e refiz a um curso inteiro de aulas assistidas sem escrever uma linha.