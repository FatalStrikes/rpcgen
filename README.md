## Commands (server):

`make -f Makefile.fibonnaci_threads`

`g++ fibonnaci_threads_server.c fibonnaci_threads_svc.c -o fibonnaci_threads_server -pthread`

`sudo ./fibonnaci_threads_server`

## Commands (host):

`./fibonnaci_threads_client localhost [0-2]`
