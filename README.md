Projeto para inserção de dados de arquivos no banco de dados 
#Projeto localizado na ramificação master

#Configurações Gerais 
Para execução correta do projeto é necessario executar os scripts na pasta files no banco de dados e alterar as configurações no properties localizado na pasta resources, de acordo com o banco de dados do usuário que irá executar o programa.

#Como o programa funciona? 
O programa tem como objetivo migrar os dados dos arquivos dados_bancarios.csv e pessoas.csv para o banco de dados SQL, os arquivos estão localizados na pasta files. Caso haja algum dados incorreto ou faltando o pragram irá adcionar no arquivo pessoas_invalidas.csv e os dados referentes não irão para o banco de dados.
