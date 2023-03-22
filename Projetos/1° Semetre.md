1º Semestre de 2020


### Parceiro Acadêmico
Fatec Prof. Jessen Vidal (proposta realizada pelo docente responsável pela disciplina que ordenou o projeto)


### Visão do Projeto

Desenvolver um sistema para a automação de uma casa residencial, criando uma interface com o cliente, onde pode apagar/acender as luzes, abrir portão, aquecer piscina, abrir porta com senha.

### Tecnologias adotadas na solução

#### Interface com o usuário - App Inventor

A interface com o cliente foi realizada através de uma tela de smartphone. Um aplicativo desenvolvido através da ferramenta App Inventor, para o sistema operacional Android, provia ao usuário final as telas de seleção de todos os eletronicos mapeados pelo cliente que ele deseja que seja automatizado.

A programação nesta plataforma se dá em blocos. Diversos recursos de linguagens de programação tradicionais (condições, loops e operações) em blocos ilustrativos, que tornam a construção de rotinas e lógicas visuais e, desta forma, mais intuitivas.

Por conta desta natureza da ferramenta - [App Inventor](https://appinventor.mit.edu/)

![App Inventor Logo](https://github.com/guitambau/PortifolioFatecApi/blob/main/IMG/app-inventor.png)

#### Arduino 

O funcionamento da casa automatizada foi construído utilizando o Arduino, com a placa central e um módulo Bluetooth HC-05.

O Arduino é uma plataforma de prototipagem. Usualmente, ao falar em "Arduino", nos remetemos a placa central que liga diversos dispositivos que são interligados por ela.

Entretanto, o Arduino como plataforma vai um pouco além, pois também fornece diversos recursos - comunicação Serial, alimentação elétrica, periféricos da propria plataforma, etc - que facilitam a prototipagem de sistemas embarcados, e que podem servir às mais diversas finalidades específicas.

Estes recursos facilitam a construção de protótipos das mais diversas finalidades. A programação simples e direta de periféricos como motores, luzes e sensores, tornam quase que ilimitadas as possibilidades de protótipos que podem ser construídas utilizando o Arduino.

O Servo Motor ou o módulo HC-05, dentre outros, fazem parte desta plataforma e foram utilizados neste projeto. Estes dispositivos em conjunto possibilitam a prototipagem de sistemas embarcados. E, neste exemplo, de um que seria responsável apenas por receber instruções para abrir e trancar uma porta.
