ls_test:	test.cpp /usr/local/lib/libslave.a
	g++ -g -o $@ $< -lslave -L/usr/local/lib -I/usr/local/include -I/usr/include/mysql -lmysqlclient
clean:
	rm -f *.o ls_test *~
