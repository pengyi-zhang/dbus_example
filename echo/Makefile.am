dbusxx_xml2cpp = dbusxx-xml2cpp

bin_PROGRAMS = echo-server

echo_server_SOURCES = echo-server-glue.h echo-server.h echo-server.cpp
echo_server_CPPFLAGS = $(DBUS_CPP_CFLAGS)
echo_server_LDADD = $(DBUS_CPP_LIBS)

echo-server-glue.h: echo-introspect.xml
	$(dbusxx_xml2cpp) $^ --adaptor=$@ 
