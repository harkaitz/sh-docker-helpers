DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/docker-h-delete  $(DESTDIR)$(PREFIX)/bin
	cp bin/docker-h-exec    $(DESTDIR)$(PREFIX)/bin
	cp bin/dsh              $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-docker-helpers
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-docker-helpers
## -- license --
