# projetomachado

A ideia geral do projeto é criar uma base de dados com as obras de Machado de Assis que estão disponíveis em Domínio Público. Essa database, então, pode ser utilizada para diferentes tarefas - tais como aplicações especializadas na literatura de Machado, ou mesmo um LLM que se expresse de acordo com o estilo machadiano.

O resultado é um database com 306.409 linhas de 1000 caracteres.

![Machado de Assis aos 57 anos](https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Machado_de_Assis_aos_57_anos.jpg/409px-Machado_de_Assis_aos_57_anos.jpg)

Para realizar esse projeto, criei primeiro um crawler que recuperasse a partir do site do Domínio Público todas as obras de Machado de Assis: [1.1 Projeto Machado: Crawlers no drive](https://github.com/ethelbeluzzi/projetomachado/blob/main/crawlers.ipynb).

Em seguida, transformei esses PDFs em um arquivo .txt com 1000 caracteres por linha, fiz a padronização e normalização do arquivo  e então sua conversão para .json: [1.2 Projeto Machado: Construindo database](https://github.com/ethelbeluzzi/projetomachado/blob/main/construindo_database.ipynb).

O arquivo .txt está [disponível aqui](https://github.com/ethelbeluzzi/projetomachado/blob/main/textonormalizado1000.txt). O arquivo em .json ficou muito grande para ser upado.

Os códigos foram gerados no Google Colab e salvam os arquivos no drive.

Os arquivos originais possuem licença apenas para uso com finalidade educativa. Então, caso deseje usar a database para seu projeto, é importante lembrar desse detalhe :)
