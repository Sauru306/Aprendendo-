import random
while True:
  pergunta = int(input("                 o(≧o≦)o\n    (>'o')> ~= ROLE OS DADOS =~ <('o'<) \n                 (─‿‿─)\n             ☆=============☆\n☆===========☆ ~By: Sauru~  ☆===========☆\n☆ 1-D2                                  ☆\n☆ 2-D4                                  ☆\n☆ 3-D6                                  ☆\n☆ 4-D8                                  ☆\n☆ 5-D10                                 ☆\n☆ 6-D20                                 ☆\n☆ 7-Sair                                ☆\n ☆=====================================☆\n        Escolha um dos dados acima: \n=======>  "))
  escolha = 0
  if pergunta == 1: 
    escolha = random.randint(1,2)
    print(escolha)
  elif pergunta == 2: 
    escolha = random.randint(1,4)
    print(escolha)
  elif pergunta == 3:
    escolha = random.randint(1,6)
    print(escolha)
  elif pergunta == 4:
    escolha = random.randint(1,8)
    print(escolha)
  elif pergunta == 5:
    escolha = random.randint(1,10)
    print(escolha)
  elif pergunta == 6:
    escolha = random.randint(1,20)
    print(escolha)
  if pergunta == 7:
    print("Bye bye, volte sempre! (^～^) ")
    break
