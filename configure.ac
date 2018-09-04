AC_INIT([aws-progs],[0.1],[thomas.epperson@gmail.com])
AM_INIT_AUTOMAKE([-Wall -Werror subdir-objects foreign])

AC_CHECK_LIB([mbedx509],[main],[], [
  AC_MSG_ERROR([Unable to find mbedx509 library])
])

AC_CHECK_LIB([mbedcrypto],[main],[], [
  AC_MSG_ERROR([Unable to find mbedcrypto library])
])

AC_CHECK_LIB([dl],[main],[], [
  AC_MSG_ERROR([Unable to find dl library])
])

AC_CHECK_LIB([pthread],[main],[], [
  AC_MSG_ERROR([Unable to find pthread library])
])

AC_CHECK_LIB([mbedtls],[main],[], [
  AC_MSG_ERROR([Unable to find mbedtls library])
])

AC_CHECK_LIB([AwsIotSdk],[main],[], [
  AC_MSG_ERROR([Unable to find awsIotSdk library])
])

AC_PROG_CC
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
