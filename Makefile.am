EXTRA_DIST = \
	Faba \
	COPYING \
	AUTHORS \
	README.md

xsessiondir = $(datadir)/xsessions

themedir = $(datadir)/icons

install-data-hook:
	$(MKDIR_P) $(DESTDIR)/usr/share/icons
	cp -R Faba $(DESTDIR)/usr/share/icons/.

uninstall-hook:
	test -e $(DESTDIR)/usr/share/icons/Faba && rm -rfv $(DESTDIR)/usr/share/icons/Faba
