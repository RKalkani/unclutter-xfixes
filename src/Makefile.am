AM_CFLAGS = $(XDEPS_CFLAGS) -I$(top_srcdir)/include
AM_CFLAGS += -Wall -Wundef -Wshadow -Wformat-security
LDADD = $(XDEPS_LIBS) -lev

bin_PROGRAMS = unclutter-xfixes
unclutter_xfixes_SOURCES = unclutter.c extensions.c cursor.c event.c util.c
