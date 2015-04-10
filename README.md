Frase para o final da prova: "Je suis un développeur, pas un ingénieur électricien."

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

## Comunicação serial.

É o processo de enviar dados um bit de cada vez, sequencialmente, num canal de comunicação ou barramento. É usada em toda comunicação de longo alcance e na maioria das redes de computadores. Exemplos: Ethernet, Serial ATA

## Comunicação paralela.

É o processo de enviar dados em que todos os bits de um símbolo são enviados juntos. A comunicação paralela implica mais de um fio, além da conexão de alimentação. Exemplos: ATA, ISA

## Comunicação serial x Comunicação paralela.

A diferença entre os dois é a quantidade de fios distintos na camada física usados para a transmissão simultânea dos dados a partir de um dispositivo.



## Interrupções.

Quando um evento (ex: apertar um botão) é enviado a unidade de processamento, esse evento é chamado de 'Interrupt'

## Protocolos de comunicação (i2c, SPI, UART).

## Timers e counters.

# Timers

A frequência do oscilador é definido com precisão e muito estável, que gera os impulsos estão sempre com a mesma largura, o que os torna ideal para a medição de tempo.

# Counters

Os pulsos de entrada se transforma em um contador, desta forma, ela não pode ser usado para medição de tempo, mas pode ser usado por exemplo para contar o número de rotação de um eixo.

A diferença do contador, os pulsos passam a ser contados a partir das portas e a sua duração (width) na maioria das vezes não está definido.

## Von Neumann e Harvard.

* A principal diferença entre as duas arquiteturas apresentadas aqui é que a arquitetura de Harvard separa o armazenamento e o trafego das instruções da CPU e dos dados em duas unidades distintas de memória, enquanto a Von Neumann utiliza o mesmo espaço de memória para ambos. Nos CPUs atuais, é mais comum encontrar a arquitetura Von Neunmann, por ser uma arquitetura mais simples, mas devido a necessidade de se almentar o desempenho, algumas características  da arquitetura Harvard também são encontradas.

## RISC e CISC.

## Prescaler.

* Circuito eletrônico de contagem usado para reduzir um sinal elétrico de alta frequência para uma frequencia mais baixa por uma divisão de um inteiro;

## Watchdog.

Um watchdog timer é um dispositivo eletrônico temporizador que dispara um reset ao sistema se o programa principal, devido a alguma condição de erro, deixar de fazer reset no watchdog timer. Trata-se de um sistema emergencial. Quando ativado, precisamos zerar o Watchdog, caso contrário, ele vai estourar e resetar o sistema.
