# projetomachado

A ideia geral do projeto é criar uma base de dados com as obras de Machado de Assis que estão disponíveis em Domínio Público. Essa database, então, pode ser utilizada para diferentes tarefas - tais como aplicações especializadas na literatura de Machado, ou mesmo um LLM que se expresse de acordo com o estilo machadiano.

Para realizar esse projeto, criei primeiro um crawler que recuperasse a partir do site do Domínio Público todas as obras de Machado de Assis: arquivo 1.1 Projeto Machado: Crawlers no drive .

Em seguida, transformei esses PDFs em um arquivo .txt com 1000 caracteres por linha, fiz a padronização e normalização do arquivo (arquivo databasemachado.txt), e então sua conversão para .json (databasemachado.json):
arquivo: 1.2 Projeto Machado: Construindo database
