# Makefile.in generated by automake 1.16.3 from Makefile.am.
# lib/snmplib/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2020 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/squid
pkgincludedir = $(includedir)/squid
pkglibdir = $(libdir)/squid
pkglibexecdir = $(libexecdir)/squid
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-portbld-freebsd11.4
host_triplet = x86_64-portbld-freebsd11.4
subdir = lib/snmplib
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/acinclude/ax_with_prog.m4 \
	$(top_srcdir)/acinclude/init.m4 \
	$(top_srcdir)/acinclude/squid-util.m4 \
	$(top_srcdir)/acinclude/compiler-flags.m4 \
	$(top_srcdir)/acinclude/os-deps.m4 \
	$(top_srcdir)/acinclude/krb5.m4 $(top_srcdir)/acinclude/pam.m4 \
	$(top_srcdir)/acinclude/pkg.m4 \
	$(top_srcdir)/acinclude/lib-checks.m4 \
	$(top_srcdir)/acinclude/ax_cxx_compile_stdcxx_11.m4 \
	$(top_srcdir)/acinclude/ax_cxx_0x_types.m4 \
	$(top_srcdir)/src/auth/basic/helpers.m4 \
	$(top_srcdir)/src/auth/basic/DB/required.m4 \
	$(top_srcdir)/src/auth/basic/LDAP/required.m4 \
	$(top_srcdir)/src/auth/basic/NCSA/required.m4 \
	$(top_srcdir)/src/auth/basic/NIS/required.m4 \
	$(top_srcdir)/src/auth/basic/PAM/required.m4 \
	$(top_srcdir)/src/auth/basic/POP3/required.m4 \
	$(top_srcdir)/src/auth/basic/RADIUS/required.m4 \
	$(top_srcdir)/src/auth/basic/SASL/required.m4 \
	$(top_srcdir)/src/auth/basic/SMB/required.m4 \
	$(top_srcdir)/src/auth/basic/SMB_LM/required.m4 \
	$(top_srcdir)/src/auth/basic/SSPI/required.m4 \
	$(top_srcdir)/src/auth/basic/fake/required.m4 \
	$(top_srcdir)/src/auth/basic/getpwnam/required.m4 \
	$(top_srcdir)/src/auth/digest/helpers.m4 \
	$(top_srcdir)/src/auth/digest/eDirectory/required.m4 \
	$(top_srcdir)/src/auth/digest/file/required.m4 \
	$(top_srcdir)/src/auth/digest/LDAP/required.m4 \
	$(top_srcdir)/src/auth/negotiate/helpers.m4 \
	$(top_srcdir)/src/auth/negotiate/SSPI/required.m4 \
	$(top_srcdir)/src/auth/negotiate/kerberos/required.m4 \
	$(top_srcdir)/src/auth/negotiate/wrapper/required.m4 \
	$(top_srcdir)/src/auth/ntlm/helpers.m4 \
	$(top_srcdir)/src/auth/ntlm/fake/required.m4 \
	$(top_srcdir)/src/auth/ntlm/SMB_LM/required.m4 \
	$(top_srcdir)/src/auth/ntlm/SSPI/required.m4 \
	$(top_srcdir)/src/log/helpers.m4 \
	$(top_srcdir)/src/log/DB/required.m4 \
	$(top_srcdir)/src/log/file/required.m4 \
	$(top_srcdir)/src/acl/external/helpers.m4 \
	$(top_srcdir)/src/acl/external/AD_group/required.m4 \
	$(top_srcdir)/src/acl/external/LDAP_group/required.m4 \
	$(top_srcdir)/src/acl/external/LM_group/required.m4 \
	$(top_srcdir)/src/acl/external/delayer/required.m4 \
	$(top_srcdir)/src/acl/external/SQL_session/required.m4 \
	$(top_srcdir)/src/acl/external/eDirectory_userip/required.m4 \
	$(top_srcdir)/src/acl/external/file_userip/required.m4 \
	$(top_srcdir)/src/acl/external/kerberos_ldap_group/required.m4 \
	$(top_srcdir)/src/acl/external/session/required.m4 \
	$(top_srcdir)/src/acl/external/time_quota/required.m4 \
	$(top_srcdir)/src/acl/external/unix_group/required.m4 \
	$(top_srcdir)/src/acl/external/wbinfo_group/required.m4 \
	$(top_srcdir)/src/http/url_rewriters/helpers.m4 \
	$(top_srcdir)/src/http/url_rewriters/fake/required.m4 \
	$(top_srcdir)/src/http/url_rewriters/LFS/required.m4 \
	$(top_srcdir)/src/security/cert_validators/helpers.m4 \
	$(top_srcdir)/src/security/cert_validators/fake/required.m4 \
	$(top_srcdir)/src/security/cert_generators/helpers.m4 \
	$(top_srcdir)/src/security/cert_generators/file/required.m4 \
	$(top_srcdir)/src/store/id_rewriters/helpers.m4 \
	$(top_srcdir)/src/store/id_rewriters/file/required.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/include/autoconf.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LTLIBRARIES = $(noinst_LTLIBRARIES)
libsnmplib_la_LIBADD =
am_libsnmplib_la_OBJECTS = asn1.lo parse.lo snmp_vars.lo \
	coexistance.lo snmp_api.lo snmp_error.lo mib.lo \
	snmp_api_error.lo snmp_msg.lo snmp_pdu.lo snmplib_debug.lo
libsnmplib_la_OBJECTS = $(am_libsnmplib_la_OBJECTS)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = 
depcomp = $(SHELL) $(top_srcdir)/cfgaux/depcomp
am__maybe_remake_depfiles = depfiles
am__depfiles_remade = ./$(DEPDIR)/asn1.Plo ./$(DEPDIR)/coexistance.Plo \
	./$(DEPDIR)/mib.Plo ./$(DEPDIR)/parse.Plo \
	./$(DEPDIR)/snmp_api.Plo ./$(DEPDIR)/snmp_api_error.Plo \
	./$(DEPDIR)/snmp_error.Plo ./$(DEPDIR)/snmp_msg.Plo \
	./$(DEPDIR)/snmp_pdu.Plo ./$(DEPDIR)/snmp_vars.Plo \
	./$(DEPDIR)/snmplib_debug.Plo
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(libsnmplib_la_SOURCES)
DIST_SOURCES = $(libsnmplib_la_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/cfgaux/depcomp
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} '/opt/squid-4.15/cfgaux/missing' aclocal-1.16
ADAPTATION_LIBS = adaptation/libadaptation.la
AIOLIB = -lrt
ALLOCA = 
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = /usr/bin/ar
AR_R = /usr/bin/ar r
ATOMICLIB = 
AUTH_LIBS_TO_BUILD =  basic/libbasic.la digest/libdigest.la negotiate/libnegotiate.la ntlm/libntlm.la
AUTH_MODULES =  basic digest negotiate ntlm
AUTOCONF = ${SHELL} '/opt/squid-4.15/cfgaux/missing' autoconf
AUTOHEADER = ${SHELL} '/opt/squid-4.15/cfgaux/missing' autoheader
AUTOMAKE = ${SHELL} '/opt/squid-4.15/cfgaux/missing' automake-1.16
AWK = nawk
BASIC_AUTH_HELPERS =  DB SMB_LM NCSA PAM POP3 RADIUS fake getpwnam
BUILDCXX = c++
BUILDCXXFLAGS =   -I/usr/include -I/usr/include -O2 -pipe -fstack-protector-strong -fno-strict-aliasing   -I/usr/local/include
BZR = 
CACHE_EFFECTIVE_USER = squid
CC = cc
CCDEPMODE = depmode=gcc3
CFLAGS =  -I/usr/include -O2 -pipe  -fstack-protector-strong -fno-strict-aliasing  -I/usr/local/include
CGIEXT = .cgi
CHMOD = /bin/chmod
CPP = cpp
CPPFLAGS = -I/usr/include -I/usr/local/include
CRYPTLIB = -lcrypt
CXX = c++
CXXCPP = c++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS =  -I/usr/include -I/usr/include -O2 -pipe -fstack-protector-strong -fno-strict-aliasing   -I/usr/local/include
CYGPATH_W = echo
DEFAULT_HOSTS = /etc/hosts
DEFAULT_LOG_DIR = /var/log/squid
DEFAULT_PID_FILE = /var/run/squid/squid.pid
DEFAULT_SWAP_DIR = /var/squid/cache
DEFS = -DSQUID_SNMP=1
DEPDIR = .deps
DIGEST_AUTH_HELPERS =  file
DISK_LIBS = 
DISK_MODULES =  DiskThreads DiskDaemon AIO Blocking IpcIo Mmapped
DLLTOOL = false
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /usr/bin/egrep
EPOLL_LIBS = 
EUILIB = 
EXEEXT = 
EXPATLIB = 
EXTERNAL_ACL_HELPERS =  file_userip unix_group delayer
EXT_LIBECAP_CFLAGS = 
EXT_LIBECAP_LIBS = 
FALSE = /usr/bin/false
FGREP = /usr/bin/fgrep
GREP = grep
HAVE_CXX11 = 
INCLTDL = -I$(top_srcdir)/libltdl
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
KRB5INCS = -I/usr/include  -I/usr/include 
KRB5LIBS = -L/usr/lib -L/usr/lib -lgssapi -lgssapi_krb5 -lheimntlm -lkrb5 -lhx509 -lcom_err -lcrypto -lasn1 -lwind -lheimbase -lroken -lcrypt -pthread -L/usr/lib -lkrb5 -lhx509 -lcom_err -lcrypto -lasn1 -lwind -lheimbase -lroken -lcrypt -pthread 
LBERLIB = -llber
LD = /usr/bin/ld
LDAPLIB = -lldap
LDFLAGS =    -pthread -L/usr/local/lib -lpcreposix -lpcre  -fstack-protector-strong  -L/usr/local/lib -Wl,-R/usr/local/lib
LIBADD_DL = 
LIBADD_DLD_LINK = 
LIBADD_DLOPEN = 
LIBADD_SHL_LOAD = 
LIBCPPUNIT_CFLAGS = 
LIBCPPUNIT_LIBS = 
LIBGNUTLS_CFLAGS = 
LIBGNUTLS_LIBS = 
LIBLTDL = $(top_build_prefix)libltdl/libltdlc.la
LIBOBJS = 
LIBOPENSSL_CFLAGS = -I/usr/include
LIBOPENSSL_LIBS = -lcrypto -lssl
LIBPTHREADS = 
LIBS = 
LIBSASL = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIBXML2_CFLAGS = 
LIBXML2_LIBS = 
LIB_KRB5_CFLAGS = -I/usr/include  -I/usr/include 
LIB_KRB5_LIBS = -L/usr/lib -lgssapi -lgssapi_krb5 -lheimntlm -lkrb5 -lhx509 -lcom_err -lcrypto -lasn1 -lwind -lheimbase -lroken -lcrypt -pthread -L/usr/lib -lkrb5 -lhx509 -lcom_err -lcrypto -lasn1 -lwind -lheimbase -lroken -lcrypt -pthread
LINUXDOC = /usr/bin/false
LIPO = 
LN = /bin/ln
LN_S = ln -s
LOG_DAEMON_HELPERS =  file DB
LTDLDEPS = $(top_build_prefix)libltdl/libltdlc.la
LTDLINCL = -I$(top_srcdir)/libltdl
LTDLOPEN = libltdl
LTLIBOBJS = 
LT_ARGZ_H = lt__argz.h
LT_CONFIG_H = include/autoconf.h
LT_DLLOADERS =  libltdl/dlopen.la
LT_DLPREOPEN = -dlpreopen libltdl/dlopen.la 
LT_SYS_LIBRARY_PATH = 
MAINT = #
MAKEINFO = ${SHELL} '/opt/squid-4.15/cfgaux/missing' makeinfo
MANIFEST_TOOL = :
MINGW_LIBS = 
MKDIR = /bin/mkdir
MKDIR_P = ../../cfgaux/install-sh -c -d
MV = /bin/mv
NEGOTIATE_AUTH_HELPERS =  kerberos wrapper
NETTLELIB = 
NM = /usr/local/bin/nm -B
NMEDIT = 
NTLM_AUTH_HELPERS =  fake SMB_LM
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = squid
PACKAGE_BUGREPORT = http://bugs.squid-cache.org/
PACKAGE_NAME = Squid Web Proxy
PACKAGE_STRING = Squid Web Proxy 4.15
PACKAGE_TARNAME = squid
PACKAGE_URL = 
PACKAGE_VERSION = 4.15
PATH_SEPARATOR = :
PERL = /usr/local/bin/perl
PKG_CONFIG = /usr/local/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
PO2HTML = off
PO2TEXT = off
POD2MAN = /usr/local/bin/pod2man
RANLIB = ranlib
REGEXLIB = 
REPL_LIBS = liblru.a libheap.a
REPL_OBJS = repl/liblru.a repl/libheap.a
REPL_POLICIES = lru heap
RM = /bin/rm -f
SECURITY_CERTGEN_HELPERS =  file
SECURITY_CERTV_HELPERS =  fake
SED = /usr/bin/sed
SET_MAKE = 
SH = /bin/sh
SHELL = /bin/sh
SMBCLIENT = 
SNMPLIB = ../lib/snmplib/libsnmplib.la
SQUID_CFLAGS =   -D_REENTRANT
SQUID_CXXFLAGS =   -D_REENTRANT
SSLLIB = -L/usr/lib -lcrypto -lssl 
STOREID_REWRITE_HELPERS =  file
STORE_LIBS_TO_ADD =  fs/libaufs.la fs/libdiskd.la fs/librock.la fs/libufs.la
STORE_LIBS_TO_BUILD =  libaufs.la libdiskd.la librock.la libufs.la
STORE_TESTS = 
STRIP = strip
SYSTEMD_CFLAGS = 
SYSTEMD_LIBS = 
TR = /usr/bin/tr
TRUE = /usr/bin/true
URL_REWRITE_HELPERS =  fake LFS
VERSION = 3.4
WBINFO = 
WIN32_PSAPI = 
XMLLIB = 
XTRA_LIBS = -lm -lkrb5 -lgssapi -lgssapi_krb5
XTRA_OBJS = 
abs_builddir = /opt/squid-4.15/lib/snmplib
abs_srcdir = /opt/squid-4.15/lib/snmplib
abs_top_builddir = /opt/squid-4.15
abs_top_srcdir = /opt/squid-4.15
ac_ct_AR = 
ac_ct_CC = cc
ac_ct_CXX = 
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = tar --format=ustar -chf - "$$tardir"
am__untar = tar -xf -
bindir = /usr/local/sbin
build = x86_64-portbld-freebsd11.4
build_alias = amd64-portbld-freebsd11.4
build_cpu = x86_64
build_os = freebsd11.4
build_vendor = portbld
builddir = .
datadir = /usr/local/etc/squid
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-portbld-freebsd11.4
host_alias = 
host_cpu = x86_64
host_os = freebsd11.4
host_vendor = portbld
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = /usr/local/share/info
install_sh = ${SHELL} /opt/squid-4.15/cfgaux/install-sh
krb5_config = /usr/bin/krb5-config
libdir = ${exec_prefix}/lib
libexecdir = /usr/local/libexec/squid
localedir = ${datarootdir}/locale
localstatedir = /var
ltdl_LIBOBJS =  lt__argz.o
ltdl_LTLIBOBJS =  lt__argz.lo
mandir = /usr/local/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = /usr/local/sbin
sharedstatedir = ${prefix}/com
srcdir = .
subdirs =  libltdl
sys_symbol_underscore = no
sysconfdir = /usr/local/etc/squid
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
AM_CFLAGS = $(SQUID_CFLAGS)
AM_CXXFLAGS = $(SQUID_CXXFLAGS)
AM_CPPFLAGS = \
	-I$(top_srcdir) \
	-I$(top_builddir)/include \
	-I$(top_srcdir)/include

noinst_LTLIBRARIES = libsnmplib.la
libsnmplib_la_SOURCES = asn1.c parse.c snmp_vars.c \
	coexistance.c snmp_api.c snmp_error.c  \
	mib.c snmp_api_error.c   \
	snmp_msg.c \
	snmp_pdu.c  snmplib_debug.c

all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign lib/snmplib/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign lib/snmplib/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLTLIBRARIES:
	-test -z "$(noinst_LTLIBRARIES)" || rm -f $(noinst_LTLIBRARIES)
	@list='$(noinst_LTLIBRARIES)'; \
	locs=`for p in $$list; do echo $$p; done | \
	      sed 's|^[^/]*$$|.|; s|/[^/]*$$||; s|$$|/so_locations|' | \
	      sort -u`; \
	test -z "$$locs" || { \
	  echo rm -f $${locs}; \
	  rm -f $${locs}; \
	}

libsnmplib.la: $(libsnmplib_la_OBJECTS) $(libsnmplib_la_DEPENDENCIES) $(EXTRA_libsnmplib_la_DEPENDENCIES) 
	$(AM_V_CCLD)$(LINK)  $(libsnmplib_la_OBJECTS) $(libsnmplib_la_LIBADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/asn1.Plo # am--include-marker
include ./$(DEPDIR)/coexistance.Plo # am--include-marker
include ./$(DEPDIR)/mib.Plo # am--include-marker
include ./$(DEPDIR)/parse.Plo # am--include-marker
include ./$(DEPDIR)/snmp_api.Plo # am--include-marker
include ./$(DEPDIR)/snmp_api_error.Plo # am--include-marker
include ./$(DEPDIR)/snmp_error.Plo # am--include-marker
include ./$(DEPDIR)/snmp_msg.Plo # am--include-marker
include ./$(DEPDIR)/snmp_pdu.Plo # am--include-marker
include ./$(DEPDIR)/snmp_vars.Plo # am--include-marker
include ./$(DEPDIR)/snmplib_debug.Plo # am--include-marker

$(am__depfiles_remade):
	@$(MKDIR_P) $(@D)
	@echo '# dummy' >$@-t && $(am__mv) $@-t $@

am--depfiles: $(am__depfiles_remade)

.c.o:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.o$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ $<

.c.obj:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.obj$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ `$(CYGPATH_W) '$<'` &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.c.lo:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.lo$$||'`;\
	$(LTCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Plo
#	$(AM_V_CC)source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) distdir-am

distdir-am: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool clean-noinstLTLIBRARIES \
	mostlyclean-am

distclean: distclean-am
		-rm -f ./$(DEPDIR)/asn1.Plo
	-rm -f ./$(DEPDIR)/coexistance.Plo
	-rm -f ./$(DEPDIR)/mib.Plo
	-rm -f ./$(DEPDIR)/parse.Plo
	-rm -f ./$(DEPDIR)/snmp_api.Plo
	-rm -f ./$(DEPDIR)/snmp_api_error.Plo
	-rm -f ./$(DEPDIR)/snmp_error.Plo
	-rm -f ./$(DEPDIR)/snmp_msg.Plo
	-rm -f ./$(DEPDIR)/snmp_pdu.Plo
	-rm -f ./$(DEPDIR)/snmp_vars.Plo
	-rm -f ./$(DEPDIR)/snmplib_debug.Plo
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
		-rm -f ./$(DEPDIR)/asn1.Plo
	-rm -f ./$(DEPDIR)/coexistance.Plo
	-rm -f ./$(DEPDIR)/mib.Plo
	-rm -f ./$(DEPDIR)/parse.Plo
	-rm -f ./$(DEPDIR)/snmp_api.Plo
	-rm -f ./$(DEPDIR)/snmp_api_error.Plo
	-rm -f ./$(DEPDIR)/snmp_error.Plo
	-rm -f ./$(DEPDIR)/snmp_msg.Plo
	-rm -f ./$(DEPDIR)/snmp_pdu.Plo
	-rm -f ./$(DEPDIR)/snmp_vars.Plo
	-rm -f ./$(DEPDIR)/snmplib_debug.Plo
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am am--depfiles check check-am clean \
	clean-generic clean-libtool clean-noinstLTLIBRARIES \
	cscopelist-am ctags ctags-am distclean distclean-compile \
	distclean-generic distclean-libtool distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
