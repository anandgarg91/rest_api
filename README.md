# Rest APIs

## Dependencies

* Spring(Boot Framework)
	sudo apt-get install spring
* Maven(Build)
	sudo apt-get install maven
* ngrok(tunneling to online IP)
	sudo apt-get install ngrok-client

## Build

* mvn spring-boot:run (Server is running at localhost port 8080)
* ngrok http 8080 (serevr will run at localhost port 4040)

## POST

* Upload API
* http://localhost:8080/uploadFile (choose multipart form file in postman)
* curl -F file=@ve_aisp.jpg http://localhost:8080/uploadFile

## GET

* Download API
* http://localhost:8080/downloadFile/cypro.jpg (postman)
* curl http://localhost:8080/downloadFile/cypro.jpg

* Trace API
* curl http://localhost:8080/getFile
