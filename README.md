# ApiDevNotes

Funções básicas de api para manipular notas na base de dados.

EndPoints:
http://server/api/getall -> GET sem parâmetros;
http://server/api/get -> GET parâmetro: id;
http://server/api/insert -> POST parâmetros: id,title,body;
http://server/api/update -> PUT parâmetros: id,title,body;
http://server/api/delete -> DELETE parâmetro: id;

Base de Dados:
1-) Criar base MySql com nome "devsnotes"
2-) Importar arquivo "notes.sql"

Recomendação para teste da api:
https://resttesttest.com/