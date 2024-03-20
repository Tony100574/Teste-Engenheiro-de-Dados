# Projeto-Engenheiro-de-Dados
Este proojeto busca demonstrar habilidades consideradas importante para um Engenheiro de Dados


Projeto engenheiro de dados



Este projeto busca demonstrar habilidades consideradas necessárias para um Engenheiro de Dados:

* 		Conhecimento em SQL
* 		Conhecimento em Python
* 		Manipulação de Dados
* 		Utilização de APIs
* 		Documentação de projetos


PARTE I

Usando SQL para responder as seguintes perguntas:

Considerando as tabelas clientes e resultado, responda o código em SQL que responde às seguintes perguntas:

* Quanto de rake foi gerado por cada Geração* de jogadores?
* Qual foi o rake gerado por mês?
* Qual sexo tem uma maior proporção de ganhadores**?


obs.: considere cada geração tendo o seguinte critério:
* Veteranos, geração  formada por pessoas que nasceram entre 1925 e 1940.  
* Baby Boomers são os nascidos entre 1941 e 1959.
* Geração X, que compreende o período de 1960 a 1979.  
* Geração Y é composta por indivíduos que nasceram entre 1980 e 1995.
* Geração Z é composta com os nascidos a partir de 1996 até 2010.
* Geração Alpha, engloba todos os nascidos a partir de 2010 até a presente data.

PARTE II

Manipulação de dados em Python


Criei um script em Python que lê os dados de uma tabela num banco MySQL, consolida os dados e salva numa outra tabela de um banco local MySQL. 

Dados  presentes na tabela raw_data. Essa tabela contém as colunas:

* datahora_acesso: o datetime em que o jogador realizou a ação
* modalidade: o tipo de jogo, podendo ser Cash Game ou Torneio
* rake: o lucro gerado por esse jogador
* clientes_id: id do jogador

A tabela consolidada tem as seguintes colunas:

* mes: o mês em que os jogadores realizaram a ação
* rake: a soma total do rake no mês
* jogadores: a quantidade distinta de jogadores que jogaram cash game ou torneio
* Rake_cash_game: a soma do rake da modalidade cash game gerado no mês
* Rake_torneio: a soma do rake da modalidade torneio gerado no mês
* jogadores_cash_game: a quantidade distinta de jogadores que jogaram cash game no mês
* jogadores_torneio: a quantidade distinta de jogadores que jogaram torneio no mês

PARTE III

Acessando APIs com Python


utilizei essa API (rapidapi(live score). Ela contem resultados de partidas de diversos esportes. Utilize o endpoint de scores para buscar determinadas informações do sport soccer_epl na resposta da API foi salva numa tabela chamada matchs_epl contendo as seguintes colunas:

* 		datahora_partida
* 		data_partida
* 		time_casa
* 		time_fora
* 		gols_time_casa
* 		gols_time_fora

