# Automação de arquivos PDF em Python
Aqui disponibilizo um projeto de automação em python, onde o programa ordena vários arquivos.pdf e mescla todos eles em um único arquivo.

## Como funciona
Criei 3 arquivos PDF com os nome de: 01.primeiro_pdf, 02.segundo_pdf e 03.primeiro_pdf. Coloquei todos eles dentro de uma pasta e usando uma biblioteca do python chamada PyPDF2, criei uma lista ordenada para organizar os arquivos. (os arquivos são ordenados de acordo com critérios específicos, como número ou data de criação.) Em seguida fiz um loof for que percorre toda a pasta dos pdfs já ordenados e junta (mescla) todos eles em um único arquivo pdf chamado de "PDF Final".

## Importante
-- Caso for baixar para testes, é necessaŕio ter o PyPDF2 instalado
Use o comando "pip install PyPDF2" (tanto no LINUX quanto no WINDOWS)
-- Os arquivos PDF devem estar na mesma pasta
-- É possível fazer isso com qualquer tipo de PDF, independente do tamanho
