AC_INIT([aws-progs],[0.1],[thomas.epperson@gmail.com])
AM_INIT_AUTOMAKE([-Wall -Werror subdir-objects foreign])

AC_CHECK_LIB([AwsIotSdk],[main],[], [
  AC_MSG_ERROR([Unable to find awsIotSdk library])
])

AC_PROG_CC
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
