# Projeto-Eletronica-USP

Projeto desenvolvido para a disciplina de Eletrônica.

INSTRUÇÕES:
Construção de uma fonte reficadora capaz de transformar corrente alternada de tensão 127 volts em uma corrente contínua, com valor de tensão ajustável entre 3 e 12 volts. 
Teremos a partir da tomada: tensão 127 volts, corrente alternada e frequência de 60 hz.

Escolha dos componentes:
(tabela do kibon)

Transformador -> 1° componente do circuito após a fonte de corrente alternada (tomada). Será responsável por reduzir de 127v a ddp proveninete da tomada para o valor desejado pela projeto (3-12v).
Obs.: o transformador apenas altera o valor da diferença de potencial entre seus terminais, não alterando de corrente alternada para corrente contínua.
 
Ponte de diodo -> utilizada para que o circuito seja abastecido com a corrente em ambos ciclos da corrente alternada.  

Capacitor -> armazena a carga durante os ciclos da corrente alternada, liberando corrente quando a tensão interna é maior que a tensão vinda da fonte. Descarrega quando ocorre a inversão de ciclo. 

Diodo Zener -> regulador de tensão máxima. Somente conduz corrente quando a tensão que chegar alcança a tensão nominal do diodo, que no caso deste projeto, será 12v. Se a tensão for menor do que 12v, o Diodo não conduz e, portanto, não interfere no circuito, se for maior, deixará a corrente passar, mantendo a tensão em 12v naquele ponto.
Informalmente, o diodo Zener “trava” o valor da tensão em 12v, que é exatamente o valor de tensão  máximo que queremos na saída da nossa fonte.

Resistores -> complementam o circuito de forma a limitar a corrente e impedindo que a corrente do circuito ultrapasse os valores limites dos componentes.

Potenciometro -> resistor variável que permitirá o controle do valor da tensão resultante entre 3 e 12 volts.

Transistor -> utilizado para permitir a passagem da corrente de forma ajustável.

Alunos:
Bernardo Marques Costa
Gabriel Freitas Ximenes de Vasconcelos  
Pedrou Augusto Ribeiro Gomes

Agradecemos ao excelentíssimo professor Eduardo do Valle Simões, o Rei.

É nois 020.
