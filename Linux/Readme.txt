For local machine 
1.To run the server program 
	First it is required to connect to the MySQL server . Create a user in MySQL and database (use given sql 	queries).
	Then in wsl install MySQL library for c using : sudo apt install libmysqlclient-dev
	Login into mysql and then run server code, compile using : gcc server.c -o server -libmysqlclient 
2.To run the client program, in another terminal compile using : g++ client.cpp -o client 
3.Start first MySQL server, then server.c code using ./server and then client.cpp using ./client
