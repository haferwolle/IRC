NULL = 

AM_CPPFLAGS = \
	$(IRCCLIENT_CFLAGS) \
	-include $(CONFIG_HEADER) \
	$(NULL)

bin_PROGRAMS = IRCClient

IRCClient_SOURCES = \
	main.vala \
	$(NULL)

IRCClient_LDADD = \
	$(IRCCLIENT_LIBS) \
	$(NULL)

IRCClient_LDFLAGS = \
	-lsqlite \
	-lgio-2.0 \
	-lgmodule-2.0 \
	$(NULL)

IRCClient_VALAFLAGS= \
	--pkg gio-2.0 \
	--pkg sqlite3 \
	--pkg gmodule-2.0 \
	--pkg libdaemon \
	--thread \
	$(NULL)

EXTRA_DIST = \
	$(NULL)

DISTCLEANFILES = \
	$(NULL)

