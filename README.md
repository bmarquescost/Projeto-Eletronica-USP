# Projeto-Eletronica-USP

## Projeto desenvolvido para a disciplina de Eletrônica.

## Instruções:

Construção de uma fonte reficadora capaz de transformar corrente alternada de tensão 127 volts em uma corrente contínua, com valor de tensão ajustável entre 3 e 12 volts. 

Teremos a partir da tomada: tensão 127 volts, corrente alternada e frequência de 60 hz.

## Escolha dos componentes:
| Quantidade | Componentes       | Valor R$ |
|------------|-------------------|----------|
| 4x         | Diodo 1N4001      | [R$0,15  x  4 = R$0,60](https://www.baudaeletronica.com.br/diodo-1n4001.html) |
| 1          | Capacitor 470uF   | [R$ 0,30](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-25v.html) |
| 1          | Led Vermelho 5mm  | [R$ 0,25](https://www.baudaeletronica.com.br/led-difuso-5mm-vermelho.html) |
| 1          | Resistor 1k ohm   | [R$ 0,08](https://www.baudaeletronica.com.br/resistor-1k-5-1-4w.html) |
| 1          | Resistor 390 ohm  | [R$ 0,08](https://www.baudaeletronica.com.br/resistor-390r-5-1-4w.html) |
| 1          | Resistor 120 ohm  | [R$ 0,08](https://www.baudaeletronica.com.br/resistor-120r-5-1-4w.html) |
| 1          | Resistor 2.2k     | [R$ 0,10](https://daeletrica.com.br/resistor-2-2k-1-4w-x10-unidades.html) |
| 1          | Potenciômetro  5k | [R$ 1,15](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html) |
| 1          | Diodo Zener (13v) | [R$ 0,21](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html) |
| 1          | Transistor NPN    | [R$ 0,18](https://www.baudaeletronica.com.br/transistor-npn-bc548.html) |
| 1          | Transformador     | [R$ 30,00](https://produto.mercadolivre.com.br/MLB-1342308413-transformador-024v-1a-trafo-bivolt-_JM?matt_tool=82322591&matt_word&gclid=EAIaIQobChMI-svhvuT_6QIVhA-RCh3n7geDEAQYAyABEgIohPD_BwE&quantity=1) |
| **Total**  |                   |  $ 33,03 |

## Os componentes

* Transformador -> 1° componente do circuito após a fonte de corrente alternada (tomada). Será responsável por reduzir de 127v a ddp proveninete da tomada para o valor desejado pela projeto (3-12v).
Obs.: o transformador apenas altera o valor da diferença de potencial entre seus terminais, não alterando de corrente alternada para corrente contínua.
 
* Ponte de diodo -> utilizada para que o circuito seja abastecido com a corrente em ambos ciclos da corrente alternada.  

* Capacitor -> armazena a carga durante os ciclos da corrente alternada, liberando corrente quando a tensão interna é maior que a tensão vinda da fonte. Descarrega quando ocorre a inversão de ciclo. 

* Diodo Zener -> regulador de tensão máxima. Somente conduz corrente quando a tensão que chegar alcança a tensão nominal do diodo, que no caso deste projeto, será 12v. Se a tensão for menor do que 12v, o Diodo não conduz e, portanto, não interfere no circuito, se for maior, deixará a corrente passar, mantendo a tensão em 12v naquele ponto.
Informalmente, o diodo Zener “trava” o valor da tensão em 12v, que é exatamente o valor de tensão  máximo que queremos na saída da nossa fonte.

* Resistores -> complementam o circuito de forma a limitar a corrente e impedindo que a corrente do circuito ultrapasse os valores limites dos componentes.

* Potenciometro -> resistor variável que permitirá o controle do valor da tensão resultante entre 3 e 12 volts.

* Transistor -> utilizado para permitir a passagem da corrente de forma ajustável.

## Imagem do circuito
<img src="./Imagens-Simulação/Simulação.png"


## Link do circuito no Falstad:
http://tinyurl.com/ya4z7x3m

## Alunos:
Bernardo Marques Costa (Odonto)

Gabriel Freitas Ximenes de Vasconcelos (Kibon)  

Pedro Augusto Ribeiro Gomes (França)

## Agradecimentos

Agradecemos ao excelentíssimo professor Eduardo do Valle Simões, o Rei.

É nois 020.
