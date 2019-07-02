# CarlosGabriel_Multimetro

# Conceito
O projeto consiste em um programa que emule o funcionamento de um multímetro, fornecendo uma maneira conveniente de medir voltagem, corrente e resistência, com o auxílio do Labview e do NI myRIO.

# Função
Com o auxílio do Labview e do NI myRIO, o usuário poderá executar medições de parâmetros elétricos e eletrônicos, como voltagem, corrente e resistência em circuitos dos mais diversos tipos.

# Motivação
A proposta consiste em facilitar a realização de verificações em circuitos e redes elétricas, dinamizando uma ferramenta imprescindível ao dia-a-dia de indivíduos envolvidos com a área.

# Interface Gráfica
O LabView facilita o desenvolvimento de uma interface gráfica mais amigável e com um maior número de ferramentas facilmente acessíveis. A seguir, um esboço da interface visível para o usuário:

![Multímetro](https://user-images.githubusercontent.com/37642374/59482578-d0486500-8e3f-11e9-9037-ad6ef9c4cd53.PNG)

O usuário poderá utilizar o knob "Seletor de caso" para escolher entre as funcionalidades Voltímetro, Amperímetro e Ohmímetro. O usuário também deverá indicar os valores de resistência interna que serão utilizados pelo multímetro durante as funções Ohmímetro e Amperímetro. Após realizar as medidas necessárias, o usuário poderá encerrar a execução através do botão STOP.

# Fluxograma
O fluxograma abaixo ilustra o funcionamento do programa:
<img src="https://user-images.githubusercontent.com/37642374/60514758-86210980-9cb0-11e9-8b2c-3f34da3aa8ec.png" height="900" width="700">

# Diagrama de Classes
Devido à natureza do programa, não foi necessária a utilização de programação orientada a objeto para o seu desenvolvimento. Assim, não se aplica o desenvolvimento de um diagrama de classes.

# Compilação
O programa é compilado pelo LabVIEW ao ser executado. Para tanto, basta instalar o LabVIEW 2019 myRIO Toolkit, o LabVIEW 2019 Real-Time Module e seguir o guia da aba de instalação do próprio myRIO, que surge automaticamente quando o aparelho é conectado ao computador.

Link para download do LabVIEW 2019 myRIO Toolkit:
http://www.ni.com/pt-br/support/downloads/software-products/download.labview-myrio-toolkit.html#305910

Link para download do LabVIEW 2019 Real-Time Module:
https://www.ni.com/pt-br/support/downloads/software-products/download.labview-real-time-module.html#305486
