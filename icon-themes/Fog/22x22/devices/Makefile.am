themedir = $(datadir)/icons/Fog
size = 22x22
context = devices

iconsdir = $(themedir)/$(size)/$(context)

icons_DATA =			\
	computer.png		\
	video-display.png

EXTRA_DIST =		\
	$(icons_DATA)

if LEGACY_ICON_MAPPING
install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context))
endif
