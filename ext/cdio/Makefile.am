plugin_LTLIBRARIES = libgstcdio.la

libgstcdio_la_SOURCES = \
	gstcdio.c \
	gstcdiocddasrc.c

libgstcdio_la_CFLAGS = \
	$(GST_PLUGINS_BASE_CFLAGS) \
	$(GST_BASE_CFLAGS) \
	$(GST_CFLAGS) \
	$(CDIO_CFLAGS)

libgstcdio_la_LIBADD = \
	$(GST_PLUGINS_BASE_LIBS) -lgstaudio-$(GST_API_VERSION) -lgsttag-$(GST_API_VERSION) \
	$(GST_BASE_LIBS) \
	$(CDIO_LIBS)

libgstcdio_la_LDFLAGS = $(GST_PLUGIN_LDFLAGS) 
libgstcdio_la_LIBTOOLFLAGS = $(GST_PLUGIN_LIBTOOLFLAGS)

noinst_HEADERS = \
	gstcdio.h \
	gstcdiocddasrc.h
