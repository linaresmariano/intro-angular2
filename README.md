# intro-angular2
Probando Angular 2


Webpack constante

	node node_modules/webpack/bin/webpack.js --watch

	

Levantar Node

	npm start



Prueba greet

	http://localhost:3001/greet?nombre=SeniorThompson



Postear noticia

	curl -X POST -H 'Content-Type: application/json' -d '{ "title": "Noticia 1", "content": "Contenido de la noticia" }' localhost:3001/noticias



Obtener noticias

	curl -i -X GET localhost:3001/noticias