bin_PROGRAMS = dummy
EXTRA_DIST = $(TESTS)

TESTS =
XFAIL_TESTS =
TESTS += tests/xfail.sh
TESTS += tests/pass.sh
TESTS += tests/skip.sh
XFAIL_TESTS += tests/xfail.sh

dummy_SOURCES = src/main.c
dummy_CFLAGS = -ggdb -pedantic -Wall -Wextra
