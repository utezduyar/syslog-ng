if ENABLE_CRITERION

modules_date_tests_TESTS = \
	modules/date/tests/test_date

check_PROGRAMS += \
	${modules_date_tests_TESTS}

modules_date_tests_test_date_CFLAGS = $(TEST_CFLAGS) -I$(top_srcdir)/modules/date
modules_date_tests_test_date_LDADD = $(TEST_LDADD)
modules_date_tests_test_date_LDFLAGS = \
	-dlpreopen $(top_builddir)/modules/date/libdate.la
modules_date_tests_test_date_DEPENDENCIES = $(top_builddir)/modules/date/libdate.la

endif
