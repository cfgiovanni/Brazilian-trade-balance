# Brazilian-trade-balance

#### Download e análise das transações da indústria brasileira (desde 1997)

Com as especificações de tipo de comércio e ano fornecidas pelo usuário, o programa checa a existência do arquivo no diretório e, se necessário, baixa o arquivo de uma base de dados do Ministério do Desenvolvimento, Indústria e Comércio Exterior por meio da bibioteca urllib. Com os dados no diretório, o programa faz a análise gráfica e estatística dos valores de exportação/importação por estado e país de destino ou procedência. 

This program reads the user input regarding the kind of financial transaction (exportation or importation) and the year of said transactions. Then it checks if the csv file exists in the current directory. In case the path is not an existing regular file, the script downloads the csv file from a database on the Brazilian Ministry of Development, Industry and Foreign Trade website, and then generates a set of graphical representations of the data.
