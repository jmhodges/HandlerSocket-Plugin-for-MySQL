AM_INCLUDES= -I. -I.. -I../hsutils
ACLOCAL_AMFILES= $$ACLOCAL_ARGS

lib_LTLIBRARIES= libhsclient.la
libhsclient_la_SOURCES= hstcpcli.cpp
libhsclient_la_CFLAGS= $(AM_CFLAGS) $(AM_INCLUDES)
libhsclient_la_CXXFLAGS= $(AM_CFLAGS) $(AM_INCLUDES)
libhsclient_la_LDFLAGS= -module ../hsutils/.libs/libhsutils.a
