fontconfigdir=$(sysconfdir)/fonts/conf.d
fontconfigavaildir=$(sysconfdir)/fonts/conf.avail
fontconfigavail_DATA=fontconfig/69-language-selector-droid.conf

install-data-hook:
	$(MKDIR_P) $(DESTDIR)$(fontconfigdir)
	$(LN_S) $(DESTDIR)$(fontconfigavaildir)/69-language-selector-droid.conf $(DESTDIR)$(fontconfigdir)/69-language-selector-droid.conf

uninstall-hook:
	$(RM) $(DESTDIR)$(fontconfigdir)/69-language-selector-droid.conf
