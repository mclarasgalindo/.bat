# Calendario.bat
![sistemas operacionais](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZG1ucGIyYjN1bnM1MGV4NG1pdnM2YnBwZW16YndmYmNpbHR0M2dodiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/C5zzP0umvvCg6KccPr/giphy.gif)

## Descrição do scripit
Esse script faz algumas coisas bem simples, mas úteis. Primeiro, ele cria duas pastas para a gente, se elas ainda não existirem. Depois, ele calcula quantos dias tem no mês que a gente escolher. Por exemplo, se você escolher o mês 1 (janeiro), ele vai mostrar que tem 31 dias. Se for fevereiro, ele coloca 28 dias. Por fim, ele mostra essa informação na tela e volta para as pastas anteriores. É uma forma fácil de organizar e calcular os dias sem precisar fazer tudo manualmente!Claro, vou explicar o que o script faz de forma bem simples!
Imagine que você tem um programa que realiza algumas ações para organizar arquivos e calcular quantos dias um mês tem. O que esse script faz é bem básico e usa um tipo de "instrução" para o computador, chamada de batch.
@echo off: Desliga a exibição de comandos enquanto o script roda.

### Exemplo:
@echo off: Isso é apenas uma forma de esconder alguns detalhes enquanto o script roda. Ele só vai mostrar o que você pedir no final.

#### Verificar se o diretório existe e criar se não existir:

O script começa verificando se uma pasta (diretório) existe. Se não existir, ele cria essa pasta. Essa pasta é chamada de %1. A parte %1 é o primeiro valor que você passa para o script. Pode ser algo como C:\MeusArquivos.

Depois, ele entra nessa pasta, usando cd "%1", que é como se estivesse entrando nela para fazer mais coisas.

##### Verificar e criar a segunda pasta:

O script então verifica se existe uma segunda pasta, chamada %2. Se não existir, ele cria também.
Depois, ele entra nessa segunda pasta.

#### Configurar o mês e calcular os dias:
O script pega o valor que você passou como o segundo parâmetro, chamado %2. Esse valor é o mês (por exemplo, "1" para janeiro, "2" para fevereiro, etc.).
Ele começa com um comando "echo oi", mas isso não faz nada muito importante, só um "oi" simples.
Depois, ele verifica qual é o mês e coloca a quantidade de dias desse mês na variável dias. Por exemplo, se o mês for 1 (janeiro), ele define que o mês tem 31 dias. Se for fevereiro (mês 2), ele coloca 28 dias (o script não trata anos bissextos, mas podemos adicionar isso mais tarde se for necessário).


#### Mostrar o número de dias no mês:
Depois de fazer esses cálculos, ele mostra na tela algo como: "O número de dias no mês 1 é 31", ou o número de dias correspondente.
Voltar para o diretório anterior:

Por fim, ele sai da segunda pasta e volta para a pasta inicial, usando cd .. (que é como voltar para trás).
Exemplo do que acontece se você rodar o script:
Suponha que você execute o script com os seguintes parâmetros:
meu_script.bat "Pasta1" "5"

Primeiro, ele vai criar a pasta "Pasta1" se não existir.
Depois, entra na "Pasta1" e cria outra pasta (chamada "5") se não existir.
Ele vai verificar que o mês é 5 (maio) e vai definir que o mês tem 31 dias.
Depois, vai mostrar na tela: "O número de dias no mês 5 é 31".
No final, ele volta para a pasta onde o script foi executado.

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
