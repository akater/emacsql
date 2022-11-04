-include ../.config.mk

.POSIX:
LDLIBS = -ldl -lm -lsqlite3

emacsql-sqlite: emacsql.c
	$(CC) $(CFLAGS) $(LDFLAGS) -o $@ emacsql.c $(LDLIBS)

clean:
	rm -f emacsql-sqlite
