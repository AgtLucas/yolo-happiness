Frase para o final da prova: "Je suis un développeur, pas un ingénieur électricien."

## Clock?

* VDD / (2^n) - 1;

## Resistor

* R = V / I

## Microprocessador o que é?

* MPU;
* Multitarefa;
* Núcleo = UCP;
* Processamento alto;
* Tomadas de decisão;

## Microcontrolador o que é?

* MCU;
* All in One (Periféricos);
* Tempo real;
* Pseudomultitarefa;
* Processamento baixo;
* 0b00001010 => Sempre byte inteiro = "10 na 10";
* 0xFF => "255 na 10";

## Diferenças entre microcontrolador e microprocessador.

## Componentes do microcontrolador e do microprocessador.

## Tipos de memória.


### ROM - Read Only Memory

É um tipo de memória que permite apenas a leitura, ou seja, as suas informações são gravadas pelo fabricante uma única vez e após isso não podem ser alteradas ou apagadas, somente acessadas. Uma memória somente de leitura propriamente dita vem com seu conteúdo gravado durante a fabricação. 

### MROM - Masked ROM

É um tipo de ROM programada por máscara, tem suas posições de memória escritas pelo fabricante com as especificações do cliente. 

### OTP ROM - One Time Programmable

Esta memória ROM só pode ser programada uma única vez. Ela possui conexões formadas por fusíveis, e é programada através do ROM programer, o qual queima os fusíveis da memória para não haver uma determinada conexão. 

### UV EPROM - UV Erasable Programmable ROM

Característica idêntica ao OPT ROM

### FLASH - Flash Memory

Permite que múltiplos endereços sejam apagados ou escritos numa só operação. Memória flash é do tipo não-volátil, o que significa que não precisa de energia para manter as informações armazenadas no chip. Exemplos: Cartões de memória, flash drives USB (pen drives), SSD, MP3 Players, dispositivos como os iPods com suporte a vídeo, PDAs, armazenamento interno de câmeras digitais e celulares.

### RAM - Random Access Memory

É um tipo de memória que permite a leitura e a escrita, utilizada como memória primária em sistemas electrónicos digitais. O termo acesso aleatório identifica a capacidade de acesso a qualquer posição e em qualquer momento. É usada pelo processador para armazenar os arquivos e programas que estão sendo processados. 

### EPROM - Erasable Programmable ROM

É um tipo de chip de memória de computador que mantém seus dados quando a energia é desligada. Em outras palavras, é não-volátil. Uma EPROM é programada por um dispositivo eletrônico que dá voltagens maiores do que os usados normalmente em circuitos elétricos.

### EEPROM - Electrically Erasable Programmable ROM

EEPROM usa a eletricidade para gravar e apagar as informações nela.Tem uma escrita lenta, pois tem que apagar o conteúdo. AS informações ficam gravas por volta de 10 anos.EEPROM pode ser programada e apagada várias vezes, eletricamente. Pode ser lida um número ilimitado de vezes, mas só pode ser apagada e programada um número limitado de vezes, que variam entre as 100.000 e 1 milhão. 

## Comunicação serial.

É o processo de enviar dados um bit de cada vez, sequencialmente, num canal de comunicação ou barramento. É usada em toda comunicação de longo alcance e na maioria das redes de computadores. Exemplos: Ethernet, Serial ATA

## Comunicação paralela.

É o processo de enviar dados em que todos os bits de um símbolo são enviados juntos. A comunicação paralela implica mais de um fio, além da conexão de alimentação. Exemplos: ATA, ISA

## Comunicação serial x Comunicação paralela.

A diferença entre os dois é a quantidade de fios distintos na camada física usados para a transmissão simultânea dos dados a partir de um dispositivo.



## Interrupções.

Quando um evento (ex: apertar um botão) é enviado a unidade de processamento, esse evento é chamado de 'Interrupt'

## Protocolos de comunicação (i2c, SPI, UART).

* I2C = Inter Integrated Circuit;
  * Usado quando a distância entre os microcontroladores é curta;
  * Novas gerações de circuitos integrados;
  * Receptor e transmissor normalmente estão no mesmo PCB;
  * Conexão é estabilizada através de 2 condutores;
    * Um é usado pra transferir os dados;
    * E o outro é usado para sincronização (clock signal);

* SPI = Serial Periphereal Interface Bus

## Timers e counters.

### Timers

A frequência do oscilador é definido com precisão e muito estável, que gera os impulsos estão sempre com a mesma largura, o que os torna ideal para a medição de tempo.

### Counters

Os pulsos de entrada se transforma em um contador, desta forma, ela não pode ser usado para medição de tempo, mas pode ser usado por exemplo para contar o número de rotação de um eixo.

A diferença do contador, os pulsos passam a ser contados a partir das portas e a sua duração (width) na maioria das vezes não está definido.

## Von Neumann e Harvard.

* A principal diferença entre as duas arquiteturas apresentadas aqui é que a arquitetura de Harvard separa o armazenamento e o trafego das instruções da CPU e dos dados em duas unidades distintas de memória, enquanto a Von Neumann utiliza o mesmo espaço de memória para ambos. Nos CPUs atuais, é mais comum encontrar a arquitetura Von Neunmann, por ser uma arquitetura mais simples, mas devido a necessidade de se almentar o desempenho, algumas características  da arquitetura Harvard também são encontradas.

## RISC e CISC.

## Prescaler.

* Circuito eletrônico de contagem usado para reduzir um sinal elétrico de alta frequência para uma frequencia mais baixa por uma divisão de um inteiro;
* N x (B - A);

## Watchdog.

Um watchdog timer é um dispositivo eletrônico temporizador que dispara um reset ao sistema se o programa principal, devido a alguma condição de erro, deixar de fazer reset no watchdog timer. Trata-se de um sistema emergencial. Quando ativado, precisamos zerar o Watchdog, caso contrário, ele vai estourar e resetar o sistema.

## Registradores

### PORTA e PORTB

Estes registradores contêm o estado atual dos “port’s” de I/O. Para um exemplo de um LED:

0 = Led apagado
1 = Led acesso

### TRISA e TRISB

Estes registradores permitem configurar os pinos de I/O como entrada ou saída. Onde:

0 = Saída
1 = Entrada
