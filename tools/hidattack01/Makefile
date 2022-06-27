
CFLAGS=-Wall
LIBS=-lbluetooth

hidattack: hidattack.c sdp.c
	$(CC) $(CFLAGS) hidattack.c sdp.c -o hidattack $(LIBS)

clean:
	rm -f *.o hidattack
