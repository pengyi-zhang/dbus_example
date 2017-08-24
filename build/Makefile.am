# what flags you want to pass to the C compiler & linker
CFLAGS =
LDFLAGS =

# this lists the binaries to produce, the (non-PHONY, binary) targets in
# the previous manual Makefile
bin_PROGRAMS = dbus_listen dbus_send dbus_start_service

dbus_example_src = ../src

dbus_listen_SOURCES = $(dbus_example_src)/dbus_listen.c
dbus_listen_CFLAGS = $(DBUS_CFLAGS) $(GLIB_CFLAGS)
dbus_listen_LDADD = $(DBUS_LIBS) $(GLIB_LIBS)

dbus_send_SOURCES = $(dbus_example_src)/dbus_send.c
dbus_send_CFLAGS = $(DBUS_CFLAGS)
dbus_send_LDADD = $(DBUS_LIBS)

dbus_start_service_SOURCES = $(dbus_example_src)/dbus_start_service.c
dbus_start_service_CFLAGS = $(DBUS_CFLAGS)
dbus_start_service_LDADD = $(DBUS_LIBS)

