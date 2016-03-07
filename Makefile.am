bin_PROGRAMS = dummy
EXTRA_DIST = $(TESTS)

TESTS = tests/xfail.sh \
	tests/pass.sh \
	tests/skip.sh
XFAIL_TESTS = tests/xfail.sh

dummy_SOURCES = src/main.c
dummy_CFLAGS = -ggdb -pedantic -Wall -Wextra
