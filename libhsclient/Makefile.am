AM_INCLUDES= -I. -I..
ACLOCAL_AMFILES= $$ACLOCAL_ARGS
top_builddir=$(abs_top_builddir)
top_srcdir=$(abs_top_srcdir)

# noinst_HEADERS= allocator.hpp          config.hpp    mutex.hpp          string_util.hpp  auto_addrinfo.hpp      escape.hpp    socket.hpp         thread.hpp auto_file.hpp          fatal.hpp     string_buffer.hpp  util.hpp auto_ptrcontainer.hpp  hstcpcli.hpp  string_ref.hpp
lib_LTLIBRARIES= libhsclient.la
libhsclient_la_SOURCES= config.cpp  escape.cpp  fatal.cpp  hstcpcli.cpp  socket.cpp  string_util.cpp
libhsclient_la_CFLAGS= $(AM_CFLAGS) 
libhsclient_la_CXXFLAGS= $(AM_CFLAGS) 
libhsclient_la_LDFLAGS= -module 


