# ApiDevNotes

Funções básicas de api em php estrurado

EndPoints:<br>
http://server/api/getall -> GET sem parâmetros;<br>
http://server/api/get -> GET parâmetro: id;<br>
http://server/api/insert -> POST parâmetros: id,title,body;<br>
http://server/api/update -> PUT parâmetros: id,title,body;<br>
http://server/api/delete -> DELETE parâmetro: id;<br>

Base de Dados:<br>
1-) Criar base MySql com nome "devsnotes"<br>
2-) Importar arquivo "notes.sql"<br>

Recomendação para teste da api:<br>
https://resttesttest.com/
