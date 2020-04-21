# restapi-flask

creation of rest api:
Software required
    python3
modules required install using pip3:
    flask
    requests
    jsonify

steps:
server.py
1 The server will have the data to be sent by a rest api it may be connected to a database or anyother file formats
2 @app.route() is a decorator along with a function which denotes what to do when that url occurs
3 variable url is denoted in tags <variable>
4 send the data about required variable present in data source


client.py
1 client send a request to the server using the request modules
2 The sent request is of get method
3 The server gets the url and returns the appropriate data in json format
4 the client can read the json and display the data in anyform

note:
url specfied in the client is the same url in which the server runs check the port number properly

how to run:

1.run server using python3 server.py
check the url in your terminal and see if it same url given in your client.py
2.run client using python3 client.py
