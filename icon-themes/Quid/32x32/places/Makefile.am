themedir = $(datadir)/icons/Quid
size = 32x32
context = places

iconsdir = $(themedir)/$(size)/$(context)

icons_DATA =			\
	folder.png		\
	folder-remote.png	\
	folder-saved-search.png	\
	user-home.png

EXTRA_DIST =		\
	$(icons_DATA)

if LEGACY_ICON_MAPPING
install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context))
endif
