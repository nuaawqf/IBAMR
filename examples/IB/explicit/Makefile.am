## Process this file with automake to produce Makefile.in
include $(top_srcdir)/config/Make-rules
SUBDIRS = ex0 ex1 ex2 ex3 ex4 ex5 ex6

## Standard make targets.
examples:
	@(cd ex0 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex1 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex2 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex3 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex4 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex5 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;
	@(cd ex6 && $(MAKE) $(AM_MAKEFLAGS) $@) || exit 1;

gtest:
	@(cd ex0 && make gtest) || exit 1;
	@(cd ex1 && make gtest) || exit 1;
	@(cd ex2 && make gtest) || exit 1;
	@(cd ex3 && make gtest) || exit 1;
	@(cd ex4 && make gtest) || exit 1;
	@(cd ex5 && make gtest) || exit 1;
	@(cd ex6 && make gtest) || exit 1;

gtest-long:
	@(cd ex0 && make gtest-long) || exit 1;
	@(cd ex1 && make gtest-long) || exit 1;
	@(cd ex2 && make gtest-long) || exit 1;
	@(cd ex3 && make gtest-long) || exit 1;
	@(cd ex4 && make gtest-long) || exit 1;
	@(cd ex5 && make gtest-long) || exit 1;
	@(cd ex6 && make gtest-long) || exit 1;

