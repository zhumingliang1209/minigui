## Makefile.am for MiniGUI using the framebuffer console video driver

AM_CPPFLAGS = -I$(abs_top_srcdir)/src/include -I$(abs_top_srcdir)/include \
			            -I$(abs_top_srcdir)/src/newgal/

noinst_LTLIBRARIES = libvideo_fbcon.la
libvideo_fbcon_la_SOURCES = $(FBCON_SRCS)

FBCON_SRCS = \
    fbvideo.c fbvideo.h
