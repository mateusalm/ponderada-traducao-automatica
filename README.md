1 .
O argumento num_examples é usado para definir a quantidade de amostras utilizadas para carregar o conjunto de dados. Mudando o valor de num_examples, o tamanho do vocabulário é afetado, de forma proporcional a num_examples.
Portanto, quanto maior o vaqlor de num_examples, mais extenso será o vocabulário.

2
A tokenização em nível de palavra não é ideal para idiomas como chinês e japonês, porque, nesses idiomas, não há separadores claros, como espaços, para indicar o limite de palavras, o que torna a divisão em palavras mais complexa. 
Em vez disso, técnicas como tokenização em nível de caractere ou uso de modelos específicos como o Byte-Pair Encoding (BPE) ou SentencePiece são mais apropriadas. Essas técnicas dividem o texto em subpalavras ou caracteres, o que permite capturar padrões linguísticos sem depender de separadores explícitos entre palavras.
Esse tipo de abordagem é mais eficaz nesses idiomas, onde uma única palavra pode ser composta de múltiplos caracteres que não possuem espaçamento.
