include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_apn

mod_LTLIBRARIES     = mod_apn.la
mod_apn_la_SOURCES  = mod_apn.c

mod_apn_la_CFLAGS   = $(AM_CFLAGS)
mod_apn_la_CFLAGS   += -DFS_VERSION_MAJOR=$(SWITCH_VERSION_MAJOR)
mod_apn_la_CFLAGS   += -DFS_VERSION_MINOR=$(SWITCH_VERSION_MINOR)
mod_apn_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_apn_la_LDFLAGS  = -avoid-version -module -no-undefined -shared
