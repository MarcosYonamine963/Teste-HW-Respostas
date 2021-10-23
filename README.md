# Teste-HW-Respostas

Link do Teste: https://github.com/lsclaudino-hw/Teste-HW

## Exercício 1

Utilizando Resistor Dependente de Luz (LDR) e um Amplificador Operacional na topologia de Comparador de Histerese, assim como um potenciômetro para ajustar as tensões de limiar, tem-se o circuito apresentado abaixo:

<img src="https://user-images.githubusercontent.com/92953755/138379192-75c72d84-0ffa-435f-9554-113a34a3e045.jpg" width="585" height="414">


## Exercício 2

Iniciando-se pela Alimentação, tem-se um circuito com a Bateria de Lithium:


![Bateria_Esquematico](https://user-images.githubusercontent.com/92953755/138535172-8e3ffb57-516e-4bb9-a8d8-f7c79a5ba4c1.PNG)

Em seguida, realizando-se o circuito projetado na Questão 1, tem-se:

![Comparador_Esquematico](https://user-images.githubusercontent.com/92953755/138535249-39d4d1cb-6958-43ff-afef-6ef4dfa29c28.PNG)


E a saída desse circuito é conectada a um Pino Digital de um Arduino Uno:


![ArduinoUno_Esquematico](https://user-images.githubusercontent.com/92953755/138535306-a8119ded-3ef8-49cf-8dba-2568d35eeceb.PNG)


PDF do esquemático:

[Esquematico.pdf](https://github.com/MarcosYonamine963/Teste-HW-Respostas/files/7401929/Esquematico.pdf)


## Exercício 3

Realizando-se o Roteamento da placa, obteve-se:

![Roteamento](https://user-images.githubusercontent.com/92953755/138536662-210d519f-07bb-431b-a736-652c00ec1a4d.PNG)

E na Visualização 3D, tem-se:

![3D](https://user-images.githubusercontent.com/92953755/138536663-f5e0f904-fb95-487f-8631-6beb405e150e.PNG)

![3D_Verso](https://user-images.githubusercontent.com/92953755/138536664-43857402-48a2-40f9-92a8-b58213db48f4.PNG)

Arquivos do Projeto:
[Circuitos.zip](https://github.com/MarcosYonamine963/Teste-HW-Respostas/files/7402005/Circuitos.zip)


## Exercício 4


Um ponto positivo  da PCI apresentada é a separação entre os circuitos analógicos e digitais, evitando-se assim as interferências entre os sinais.

Outra observação importante é a separação entre as malhas do circuito analógico e a malha do circuito digital, fazendo-se assim planos de terras diferentes, conectados por pontos específicos.

As malhas de terra ou de alimentação também ajudam a manter sob controle a radiação e o crosstalk dos circuitos digitais de alta frequência. Além disso, é recomendado que as trilhas desses sinais sejam as mais curtas possíveis. Assim, uma sugestão seria mudar a localização do gerador de clock para mais próximo dos pontos de utilização, ou seja, colocá-lo entre os três circuitos integrados. Fazendo-se isso, além de reduzir o comprimento da trilha de clock, irá afastá-lo da fonte chaveada, que poderia introduzir ruídos ao clock.

Capacitores de desacoplamento são importantes para desviar os ruídos de alta frequência nos pontos de alimentação do circuito. Como observado, os cicuitos integrados já possuem capacitores de desacoplamento na alimentação. Porém, pode-se adicionar também para a fonte chaveada, reduzindo os ruídos de alta frequência que poderiam ser transmitidos para o restante do circuito.

A suavização nas curvas das trilhas aumenta o controle de impedância. O recomendado é realizar as curvas com ângulo máximo de 45 graus.

