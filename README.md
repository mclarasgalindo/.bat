# Calendario.bat
![sistemas operacionais](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZG1ucGIyYjN1bnM1MGV4NG1pdnM2YnBwZW16YndmYmNpbHR0M2dodiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/C5zzP0umvvCg6KccPr/giphy.gif)

## Descrição do scripit
Esse script faz algumas coisas bem simples, mas úteis. Primeiro, ele cria duas pastas para a gente, se elas ainda não existirem. Depois, ele calcula quantos dias tem no mês que a gente escolher. Por exemplo, se você escolher o mês 1 (janeiro), ele vai mostrar que tem 31 dias. Se for fevereiro, ele coloca 28 dias. Por fim, ele mostra essa informação na tela e volta para as pastas anteriores. É uma forma fácil de organizar e calcular os dias sem precisar fazer tudo manualmente!Claro, vou explicar o que o script faz de forma bem simples!
Imagine que você tem um programa que realiza algumas ações para organizar arquivos e calcular quantos dias um mês tem. O que esse script faz é bem básico e usa um tipo de "instrução" para o computador, chamada de batch.
@echo off: Desliga a exibição de comandos enquanto o script roda.

### Exemplo:

### Criar pastas:
Se a pasta %1 não existir, ele cria.
Entra na pasta %1.
Se a pasta %2 não existir, ele cria.
Entra na pasta %2.

### Calcular dias do mês:
O script pega o mês (%2) e define o número de dias para o mês:
Janeiro (1) → 31 dias
Fevereiro (2) → 28 dias
Março (3) → 31 dias
E assim por diante para os outros meses.

### Exibir o número de dias:
Mostra na tela quantos dias o mês tem. Exemplo: "O número de dias no mês 5 é 31".

### Voltar para as pastas anteriores:
Sai da pasta %2 e volta para a pasta %1.

## Desafios:
Não encontrei muitos desafios na hora de fazer a programação,foi no momento se separava os núneros ou deixava juntos mesmo.

## O que aprendi: 
Vi como criar pastas como se fosse um caledário com várias pastas.Vai ajudar no dia a dia facilitando criar pastas e executar elas só com códigos.

## Comandos:
#### . @echo off - Isso é apenas uma forma de esconder alguns detalhes enquanto o script roda. Ele só vai mostrar o que você pedir no final.
#### . :: - adiciona um comentário.
#### . if - permite executar comandos baseados em condições, como verificar se um arquivo existe.
#### . set- cria uma variável.
#### . mkdir- criar uma pasta.
#### . cd- para entrar dentro da pasta.

![sistemas operacionais](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZzEzdWhrZmFuZm8wNGQ1Ym9paDg0eXo0Nmt4YXg1ZnZoemlhMWpsbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LHZyixOnHwDDy/giphy.gif)
