## Process this file with automake to produce Makefile.in
#######################################################################
# gaul-devel/tests/Makefile.am
#######################################################################
#
# GAUL - Genetic Algorithm Utility library.
# Copyright ©2000-2006, Stewart Adcock <stewart@linux-domain.com>
#
# The latest version of this program should be available at:
# http://gaul.sourceforge.net/
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.  Alternatively, if your project
# is incompatible with the GPL, I will probably agree to requests
# for permission to use the terms of any other license.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY WHATSOEVER.
#
# A full copy of the GNU General Public License should be in the file
# "COPYING" provided with this distribution; if not, see:
# http://www.gnu.org/
#
#######################################################################

# require automake 1.4
AUTOMAKE_OPTIONS = 1.4

AM_CPPFLAGS = \
	-I$(top_srcdir)/util -I$(top_srcdir)/src \
	-I$(top_builddir)/util \
	-I/usr/include/slang

bin_PROGRAMS = gaul_diagnostics

noinst_PROGRAMS = test_prng test_utils test_bitstrings test_slang \
		test_io \
		test_ga test_moga \
		test_de test_sd test_sd2 \
		test_simplex test_simplex2

gaul_diagnostics_SOURCES = diagnostics.c

gaul_diagnostics_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_prng_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_utils_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_bitstrings_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_slang_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_io_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_ga_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_moga_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_de_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_sd_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_sd2_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_simplex_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
test_simplex2_LDADD = -L../src/ -L../util/ -lgaul -lgaul_util -lm @MPILIBS@
