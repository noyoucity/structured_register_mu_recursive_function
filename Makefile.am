## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src po

structured_register_mu_recursive_functiondocdir = ${prefix}/doc/structured_register_mu_recursive_function
structured_register_mu_recursive_functiondoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


INTLTOOL_FILES = intltool-extract.in \
	intltool-merge.in \
	intltool-update.in

EXTRA_DIST = $(structured_register_mu_recursive_functiondoc_DATA) \
	$(INTLTOOL_FILES)

DISTCLEANFILES = intltool-extract \
	intltool-merge \
	intltool-update \
	po/.intltool-merge-cache


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(structured_register_mu_recursive_functiondocdir)
