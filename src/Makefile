
sources = far.c

all: far

far: $(sources)
	gcc -g -o $@ $(sources)

install: $(sources)
	gcc -g -o far $(sources)
	sudo cp far /usr/bin
	chown root:root /usr/bin/far
	chmod +x /usr/bin/far

clean:
	-rm far






