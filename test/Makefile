ls_test:	test.cpp ../libslave.a
	g++ -g -o $@ $< -lslave -L/usr/local/lib -I/usr/local/include -lmysqlclient
clean:
	rm -f *.o ls_test *~
