CC=gcc
CFLAGS=-Wall -I ../lib

iaxvoipclient: iaxvoipclient.c
	$(CC) $(CFLAGS) iaxvoipclient.c  ../build/libiaxclient_lib.a -lm -pthread -lpulse-simple -lpulse -lopenal -o iaxvoipclient
