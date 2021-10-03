# Python-Base64-Encoding
:rocket: # Python Base64 Encoding

Os dados são primeiro transformados em binários e acrescidos de dígitos binários para que seu
comprimento torna-se um múltiplo de 6, então cada 6 dígitos binários corresponderão a um caractere em
a string B64_CHARSET. O número de dígitos binários anexados determinaria posteriormente
quantos sinais "=" devem ser adicionados, o preenchimento.
Para cada 2 dígitos binários adicionados, um sinal "=" é adicionado na saída.
Podemos adicionar quaisquer dígitos binários para torná-lo um múltiplo de 6, por exemplo, considere o
seguinte exemplo:
"AA" -> 0010100100101001 -> 001010 010010 1001
Como pode ser visto acima, mais 2 dígitos binários devem ser adicionados, então há 4
possibilidades aqui: 00, 01, 10 ou 11.
Dito isso, a codificação Base64 pode ser usada na esteganografia para ocultar dados nestes
dígitos anexados.
