#
# Copyright 2008 Free Software Foundation, Inc.
# Copyright 2014 Range Networks, Inc.
#
# This software is distributed under the terms of the GNU Public License.
# See the COPYING file in the main directory for details.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
#

include $(top_srcdir)/Makefile.common

DESTDIR ?= 
# must be kept in sync with AC_CONFIG_MACRO_DIR in configure.ac
ACLOCAL_AMFLAGS = -I config

#noinst_LTLIBRARIES = libSR.la

#libSR_la_SOURCES = \
#	SubscriberRegistry.cpp 

#noinst_HEADERS = \
#	SubscriberRegistry.h 

# Order must be preserved
SUBDIRS = \
	config \
	Globals \
	fixmes \
	apps

FORCE:
