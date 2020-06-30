# Socket-Base-PHP-Realtime-Chat-Application
Create a simple php chat application using WebSocket and PHP socket programming. The WebSocket is used to create a bridge to send or receive messages from the PHP chat server. In the web world, we generally use HTTP request methods to communicate between the client and server side. In this application, we use socket to communicate with the server, For establishing a socket connection between the client and the server, we use the WebSocket protocol (ws://) to specify the address of the PHP page where the WebSocket handshake is handled. After creating WebSocket there are callbacks to handle the events that occur between the client and the server during the chat process.

## Installation

To install the application please follow bellow steps one by one.

- Clone project repo.
- Make sure socket "ws" url is right as per your host Url, Mine for localhost is (ws://localhost:8090/Socket-Base-PHP-Realtime-Chat-Application/inc/php-socket.php) you can change that into index.php file easily.
- Make Sure PHP CLI is setup to your machine, specially if you are using Windows.
- Open Command prompt(CMD) and Run ```php -q PATH_TO_YOUR_PROJECT_DIRECTORY and php-socket.php FILE```
- For my case i run command ```php -q /g/xampp/htdocs/Socket-Base-PHP-Realtime-Chat-Application/inc/php-socket.php``` (You can run accordingly).

- Boom you can open multiple browser windows and can test. 
