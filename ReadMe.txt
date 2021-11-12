//////////////Para inicar la app/////////////

1ª-Activar base de datos (dentro del Cmd):
	mongod
	mongo

//importante---para los siguientes pasos tienes que ir a la direccion del archivo (mongoApp) dentro del cmd----///////

2ª-Activar el primer sensor protocolo tcp --server.js-- (dentro del cmd):
	
	node server.js

3º-Activar el consumidor-middleware  --client.js-- (dentro del cmd):
	
	node client.js

4ª Activar el procesamiento de datos rpc --serve_xmlrpc-- (dentro del cmd) y cuando aparezca la interfaz de activar de python, simplemente la cerramos(es importante cerrarla):
	
	py serve_xmlrpc.py
	
5ª Activar el sensor 2 protocolo udp --udp1.py--(dentro del cmd):

	py udp1.py

6ª Ahora nuestro index se encuetra operativo, solo queda ingresar a la pagina web y ir a la url y agregar la ip (http://ip:1000/)

							///info del index///

	Cabe mencionar que todo el index fue diseñado a mano por nosotros en su estructura y diseño, no nos alcanzo el tiempo para explicar como 
	lo hicimos, asi que solo nos enfocamos en explicar los puntos que usted solicito en la evaluacion. 