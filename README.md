
# Neste projeto foi proposto a criação do projeto e prototipagem de um circuito de carregador de telefone.
    # Parte 1 
    
* Iniciamos realizando testes de simulação pelo Proteus 8 onde foi realizada uma simulação do desenvolvimento de uma fonte de alimentação linear. 

- Componentes do Circuito:
U1: Um regulador de voltagem de 7805V. Este componente converte a voltagem de entrada variável em uma voltagem de saída fixa de 5V.
VI: A voltagem de entrada. Esta voltagem pode ser fornecida por uma bateria, um adaptador AC/DC ou outro tipo de fonte de alimentação.
VO: A voltagem de saída. Esta voltagem é a voltagem que será fornecida à carga.
TR2: Um transistor NPN. Este transistor é usado como um interruptor para controlar o fluxo de corrente através do circuito.
BR1: Uma ponte retificadora. Este componente converte a corrente alternada (CA) em corrente contínua (CC).
D2: Um diodo. Este diodo protege o transistor contra surtos de voltagem reversa.
LED-RED: Um LED vermelho. Este LED é usado como um indicador visual de que o circuito está funcionando.
C1 e C2: Capacitores. Estes capacitores filtram a voltagem de saída e reduzem o ruído.
R1: Um resistor. Este resistor limita a corrente que flui através do transistor.

- Como o Circuito Funciona:
A voltagem de entrada (VI) é aplicada à ponte retificadora (BR1), que converte a CA em CC. A CC é então filtrada pelos capacitores C1 e C2. A voltagem filtrada é então aplicada à base do transistor TR2.
Se a voltagem na base for maior que uma certa voltagem limite, o transistor ligará e permitirá que a corrente flua através do coletor para o emissor. A corrente que flui através do coletor é então aplicada à carga.
A voltagem de saída (VO) é a voltagem que aparece no coletor do transistor. A voltagem de saída pode ser ajustada alterando o valor do resistor R1.![Captura de tela 2024-03-19 211353](https://github.com/ViZanella/Sistemas-Embarcados-carregador-/assets/126624524/4e3f9b0c-fdbf-4c5d-9989-a20b5c8d26a3)
