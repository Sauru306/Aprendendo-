Aprendendo

Um compilado de pequenos projetos desenvolvidos com o objetivo de aprender e aprimorar minhas habilidades como programador.

Projeto: Dados de RPG

Introdução:

Neste primeiro projeto, tive como objetivo criar um programa de dados de RPG com 7 opções disponíveis para o usuário: 6 tipos de dados e 1 opção de saída.
Além disso, o programa foi estruturado para se repetir infinitamente até que o usuário escolhesse a sétima opção, que encerra a execução.

Como eu programei isso?

Logo na primeira linha, importei a biblioteca random para usar a função random.randint(), que retorna um número aleatório entre dois valores. Isso simula a rolagem dos dados.

Depois, utilizei a estrutura de repetição while com a condição True para criar um loop infinito, garantindo que o programa continue rodando até que o usuário decida sair.

Em seguida, criei a variável pergunta, que armazena a entrada do usuário usando a função input().
Como o input() retorna uma string por padrão, usei a função int() para convertê-la em número inteiro, já que só trabalhamos com números de 1 a 7 neste contexto.

Texto do menu exibido ao usuário:

                      o(≧o≦)o
        (>'o')> ~= ROLE OS DADOS =~ <('o'<)
                      (─‿‿─)
            ☆=======================☆
    ☆=========☆    ~ By: Sauru ~    ☆=========☆
    ☆ 1 - D2                                   ☆
    ☆ 2 - D4                                   ☆
    ☆ 3 - D6                                   ☆
    ☆ 4 - D8                                   ☆
    ☆ 5 - D10                                  ☆
    ☆ 6 - D20                                  ☆
    ☆ 7 - Sair                                 ☆
    ☆==========================================☆

             Escolha um dos dados acima:
    ===============> 

Adicionei esse layout para dar um pouco de personalidade ao projeto, mesmo com alguns "frufrus" estéticos.

Depois disso, criei a variável escolha e atribuí o valor 0 a ela. Esse valor inicial é neutro, pois seria substituído conforme a escolha do usuário.

Utilizei a estrutura condicional if para verificar o valor inserido na variável pergunta, e com base nisso, executei o bloco correspondente.
A seguir, usei elif (forma abreviada de “else if”) para lidar com as demais possibilidades, o que ajuda a deixar o código mais organizado e evita múltiplos if desnecessários.

Explicação dos blocos condicionais:
O programa simula 6 tipos de dados (D2, D4, D6, D8, D10, D20), cada um representado pelos números de 1 a 6 no menu. Por exemplo:

Se pergunta == 1, o programa executa o primeiro bloco if.

Se pergunta == 2, executa o primeiro elif, e assim por diante.

Todos os blocos if / elif seguem o mesmo padrão, mudando apenas o tipo de dado sorteado. Para simplificar, explico abaixo o primeiro if, o primeiro elif e o último if (que encerra o programa):

if pergunta == 1:

Executa random.randint(1, 2), simulando a rolagem de um D2, e armazena o valor na variável escolha.
Em seguida, imprime o resultado com print(escolha).

elif pergunta == 2:

Executa random.randint(1, 4), simulando um D4. O funcionamento é igual, apenas muda a faixa numérica.

if pergunta == 7:

Exibe a mensagem final:
print("Bye bye, volte sempre! (^～^)")
E finaliza o loop com o comando break.

Conclusão:

Neste pequeno projeto, coloquei em prática meus conhecimentos sobre:

-Criação e controle de loops

-Uso de variáveis

-Estruturas condicionais (if, elif, break)

-Entrada e saída de dados

-Importação e uso de bibliotecas externas (random)
