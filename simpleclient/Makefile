CC=gcc
CFLAGS=-Wall -I ../lib

iaxvoipclient: iaxvoipclient.c
	$(CC) $(CFLAGS) iaxvoipclient.c  ../build/libiaxclient_lib.a -lm -pthread -lasound -o iaxvoipclient
