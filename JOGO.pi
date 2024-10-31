#Python Game floresta encantada
def my_function():
  print(f"\n{'Fim de jogo' : >50}")
print("Para cada fim de narração teras de fazer uma escolha entre duas opções lá representadas,")
print(f"{'Bem-vindo a minha aventura!' : >50}")
print("\nAcordaste numa floresta encantada após um acidente do qual não te recordas.")
print("\nA tua frente vez dois caminhos no meio da floresta.")
lado = input("\nVais para a direita ou esquerda?(direita ou esquerda) ").lower()
if lado == "direita":
  print("\nSegues o caminho da direita onde encontras uma casa estranha, e entras na casa.")
  pegar=input("\nEntras na casa e encontras uma mesa ao entrar onde tem uma mochila.(pegar ou nao pegar) ").lower() 
  if pegar == "pegar":
    print("\nPegas na mochila e continuas o teu caminho, até que encontras escondido, no meio de desconbros, um bau, ao abrir o bau encontras uma faca, um machado e um enorme martelo.")
    arma = input("Qual arma desejas?(faca,machado,martelo) ").lower()
    if arma == "faca": 
      print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
      print("Atacas o mosntro porem não é o suficiente para o derrotar e morres.")
      my_function()
    elif arma == "machado":
      print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
      print("Pegas no teu machado e atacas o monstro, após uma baralha intensa tu derrotas o monstro mas devido aos ferimentos causados por ele tu acabas por morrer.")
      my_function()
    else:
      print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
      print("\nConvocas o teu enorme martelo e atacas o monstro, o martelo é muito forte e derrota o mosntro com facilidade.")
      porta = input("Continuas a tua jornada, mais a frente na casa encontras uma porta a brilhar.(entrar ou nao entrar) ").lower()
      if porta == "entrar":
        print("Entras na porta e derepente voltas ao momento antes do acidente, e consegues empedir que ele aconteça.")
        my_function()
      else: 
        print("Desides não entrar na porta")
        my_function()
  else:
    print("\nDeixas a mochila de lado e continuas o teu caminho, até que encontras escondido, no meio de desconbros, um bau, ao abrir o bau encontras uma faca, um machado e um enorme martelo.")
    arma = input("\nQual arma desejas?(faca,machado,martelo) ").lower()
    if arma == "faca": 
      print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
      print("Atacas o mosntro porem não é o suficiente para o derrotar e morres.")
      my_function()
    elif arma == "machado":
      print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
      print("Pegas no teu machado e atacas o monstro, após uma baralha intensa tu derrotas o monstro.")
      print("Segues em frente na casa onde encontras uma porta, decides entrar na porta, ao entrar nela tu vês o momento do acidente o qual não te lembravas, e percebes que morreste e estás num lugar desconhecido.")
      my_function()
    elif arma == "martelo":
      print("Não consegues portar o martelo sem a mochila.")
      arma = input("\nQual arma desejas?(faca,machado) ").lower()
      if arma == "faca": 
        print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
        print("Atacas o mosntro porem não é o suficiente para o derrotar e morres.")
        my_function()
      elif arma == "machado":
        print("Pegas na arma e continuas o teu caminho, até que te deparas com uma porta, ao entrar nela encontras uma criatura.")
        print("Pegas no teu machado e atacas o monstro, após uma baralha intensa tu derrotas o monstro.")
        print("Segues em frente na casa onde encontras uma porta, decides entrar na porta, ao entrar nela tu vês o momento do acidente o qual não te lembravas, e percebes que morreste e estás num lugar desconhecido.")
        my_function()

elif lado == "esquerda":
  print("Segues o caminho da esquerda, até que encontras uma quinta.")
  quinta = input("\nVês uma casa e um grande campo de milho.(casa,campo) ").lower()
  if quinta == "casa":
    senhor = input("\nVais até a casa e notas a porta aberta, ao entrar nela vês um senhor, porem ele ainda não te notou.(falar, nao falar) ").lower()
    if senhor == "falar":
      print("\nEle ataca-te, e causa-te um ferimento, mas consegues evitar que ele te mate, reparas num pedaço de vidro no chão e consegues usar-lo para matar o senhor.")
      print("Continuas a explorar a casa em busca de um kit de primieros socorros ou algo que te possa ajudar a estacar o sangramento do ferimento causado pelo senhor.")
      print("Chegas no que julgas ser a cave da casa e decides entrar")
      print("Ao entrar ves um monte de prateleiras cheias de ferramentas do senhor, e um tapete, ao passar por cima dele tu ouves um som estranho.")
      mulher = input("Tu decides ver oque tem lá, ao remover o tapete encontras uma escotilha, e entras por ela depois de descer umas escadas bem longas encontras uma mulher amarrada a uma cadeira presa pelo senhor.(falar ou nao falar) ").lower()
      if mulher == "falar":
        print("\nFalas com a mulher e descobres que o senhor era uma criatura disfarçada, e decides soltar e salvar a mulher.")
        print("Salvas a mulher e com a ajuda dela tratas das tuas feridas e vocês conseguem sair da casa e continuar vivos juntos.")
        my_function()
      elif mulher == "nao falar":
        print("Deixas a mulher de lado pois pode também ser perigosa, e segues sem a ajuda dela, vês umas bandagens a beira dela e usas para te curar.")
        print("Voltas a subir e vais te embora sozinho.")
        my_function()
    else:
      print("\nPassas pelo corredor sem ele te notar.")
      print("Continuas a explorar a casa e chegas no que julgas ser a cave da casa e decides entrar")
      print("Ao entrar ves um monte de prateleiras cheias de ferramentas do senhor, e um tapete, ao passar por cima dele tu ouves um som estranho.")
      mulher2 = input("Tu decides ver oque tem lá, ao remover o tapete encontras uma escotilha, e entras por ela depois de descer umas escadas bem longas encontras uma mulher amarrada a uma cadeira presa pelo senhor.(falar ou nao falar) ").lower()
      if mulher2 == "falar":
        print("\nFalas com a mulher e descobres que o senhor era uma criatura disfarçada, e decides soltar e salvar a mulher.")
        print("Sobes junto com a mulher e o senhor ouviu vos a fechar a escotilha e foi verificar...")
        print("Ele econtravos e tenta atacar-te, porém a mulher que ajudas-te pega numa ferramenta afiada que estava lá pousada e finaliza o senhor que se revela sendo uma criatura ao morrer.")
        print("Após isso tornam-se amigos e seguem o vosso caminho nesse mundo juntos.")
        my_function()
      else: 
        print("\nNão falas com a mulher pois pode ser uma ameaça e sobes de volta pois não tem lá nada que de interesse.")
        print("Ao subir fazes barulho e o senhor ouviu-te a fechar a escotilha e foi verificar... ")
        print("Ele econtra-te e tenta ataca-te, não te consegue defender sozinho perante o ataque do senhor, e ele mata-te.")
        my_function()
  else:
    print("\nVais em direção ao campo ver oque é aquela luz tão brilhante.")
    criaturacampo = input("Ao entrar no campo e passar pelo meio do milho deparaste com uma criatura estranha, ela ainda não te percebeu, tu vês uma arma no chão atrás dela, ou foges por outro lado ou pegas na arma e tentas finalizar a criatura.(fugir ou pegar arma) ").lower()
    if criaturacampo == "fugir":
      print("\nTu passas pelo meio do milho a desviar-te da criatura.")
      print("Encontras finalmente a origem da luz, é uma pedra bem brilante a flutuar.")
      print("Ao ver-la percebes que não estás no teu mundo, vais a beira da pedra mas ao tentar tocar-lhe, a criatura estranha aparece e salta para cima de ti, finalizando-te.")
      my_function()
    else:
      print("\nCorres e pegas na arma, atacas a criatura e consegues derruta-la antes que ela te consiga atacar.")
      print("Continuas a andar no meio do milho e encontras finalmente a origem da luz, é uma pedra bem brilante a flutuar.")
      pedra = input("Pegar na pedra?(pegar ou nao pegar) ").lower()
      if pedra == "pegar":
        print("\nPegas na pedra e aop tocar nela tu voltas ao teu mundo normal, num hospital e descobres que sofreste um acidente de carro do qual te apagou por dias, passado um tempo sais do hospital e voltas a tua vida normal.")
        my_function()
      else:
        print("\nDecides não tocar na pedra e continuas o teu caminho a descobrir esse mundo até que morres para criaturas dias depois de andares nesse dia.")
        my_function()
else:
  print("Erro")
