# vim:set ts=4
#
# ibus-table-zhengma - The zhengma database of Table engine for IBus
#
# Copyright (c) 2008-2009 Yu Yuwei <acevery@gmail.com>
#
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
#
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
#
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
#
# $Id: $
#

SUBDIRS = \
	icons \
	m4 \
	tables \
	docs \
	$(NULL)

dist_doc_DATA = \
	README \
	$(NULL)

ACLOCAL_AMFLAGS = -I m4

EXTRA_DIST = \
	autogen.sh \
	$(NULL)
#	@PACKAGE_NAME@.spec.in \
#	$(NULL)

noinst_DIST = \
	$(NULL)


#DISTCLEANFILES = \
#	po/stamp-it \
#	$(NULL)

#rpm: dist @PACKAGE_NAME@.spec
#	rpmbuild -bb \
#			--define "_sourcedir `pwd`" \
#			--define "_builddir `pwd`" \
#			--define "_specdir `pwd`" \
#			--define "_rpmdir `pwd`" \
#			--define "_srcrpmdir `pwd`" \
#			@PACKAGE_NAME@.spec
#
#srpm: dist @PACKAGE_NAME@.spec
#	rpmbuild -bs \
#			--define "_sourcedir `pwd`" \
#			--define "_builddir `pwd`" \
#			--define "_srcrpmdir `pwd`" \
#			--define "_rpmdir `pwd`" \
#			--define "_specdir `pwd`" \
#			@PACKAGE_NAME@.spec
#
#clean-rpm:
#	$(RM) -r "`uname -i`"
#
#clean-local: clean-rpm
