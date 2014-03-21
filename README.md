[![Build Status](https://travis-ci.org/rockdaboot/libpsl.png?branch=master)](https://travis-ci.org/rockdaboot/libpsl)

libpsl - C library to handle the Public Suffix List
===================================================

Find more information [here](http://publicsuffix.org/).
Download the Public Suffix List [here](https://hg.mozilla.org/mozilla-central/raw-file/tip/netwerk/dns/effective_tld_names.dat).

Building from git
-----------------

Download project and prepare sources with

		git clone http://github.com/rockdaboot/libpsl
		./autogen.sh
		./configure
		make
		make check
