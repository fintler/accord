AC_PREREQ([2.68])
AC_INIT([accord],[0.1],[])

AC_CONFIG_AUX_DIR(auxdir)
AC_CONFIG_MACRO_DIR([m4])

AM_INIT_AUTOMAKE([-Wall no-define])
AC_CONFIG_HEADERS([config.h])

AC_PROG_CC
AM_PROG_CC_C_O
AM_PROG_INSTALL
AC_PROG_LIBTOOL
AC_PROG_RANLIB

AC_SEARCH_LIBS([pthread_create], [pthread], [],
    [AC_MSG_FAILURE([PThreads library missing])])

AC_CHECK_HEADERS([arpa/inet.h fcntl.h limits.h memory.h netdb.h netinet/in.h])
AC_CHECK_HEADERS([stdint.h string.h sys/socket.h sys/time.h syslog.h unistd.h])

AC_C_INLINE
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_PID_T
AC_TYPE_SIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T

AC_FUNC_FORK
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([dup2 gethostname gettimeofday memset mkdir select socket])
AC_CHECK_FUNCS([strcasecmp strdup strerror])

AC_CONFIG_FILES([Makefile
                 apps/Makefile
                 apps/queue/Makefile
                 conductor/Makefile
                 libacrd/Makefile
                 test/Makefile
                 libacrd/libacrd.pc:libacrd/libacrd.pc.in])
AC_OUTPUT
