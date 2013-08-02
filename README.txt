CS454
=====

Remote Procedure Call

Created by Haochen Ding and Shisong Tang

Compile and run:
1. run make file
2. g++ -L. client.o -lrpc -o client 
3. g++ -L. server functions.o server function skels.o server.o -lrpc -o server
4. ./binder
5. Manually set the BINDER ADDRESS and BINDER PORT environment variables on the client and server machines. (Use setenv if using C shell)
6. ./server and ./client to run our server(s) and client(s). Note that the binder, client and server may be running on different machines.
