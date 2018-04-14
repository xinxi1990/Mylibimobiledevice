### 更新点
idevicecrashreport

- 1.只下载 .ips格式的crash文件,其他类型的文件不下载
- 2.增加-g || --grep参数 可以过滤crash文件名称下载文件。
例子：
```
MACdeMacBook-Pro:log MAC$ idevicecrashreport -k -g TuNiuApp .
Copy: /TuNiuApp-2017-03-21-184033.ips
Done.
MACdeMacBook-Pro:log MAC$ 
```

About
=====

A library to communicate with services of Apple iOS devices using native
protocols.

Requirements
============

Development Packages of:

	libgnutls or openssl
	libplist
	libusbmuxd

Software:

	usbmuxd
	make
	autoheader
	automake
	autoconf
	libtool
	pkg-config
	gcc

Optional:

	cython (Python bindings)
	doxygen (Documentation)

Installation
============

To compile run:

	./autogen.sh
	make
	sudo make install

Who/What/Where?
===============

Home:

	http://www.libimobiledevice.org/

Code:

	git clone http://git.libimobiledevice.org/libimobiledevice.git

Code (Mirror):

	git clone https://github.com/libimobiledevice/libimobiledevice.git

Tickets:

	http://github.com/libimobiledevice/libimobiledevice/issues

Mailing List:

	http://lists.libimobiledevice.org/mailman/listinfo/libimobiledevice-devel

IRC:

	irc://irc.freenode.net#libimobiledevice

Twitter:

	https://twitter.com/libimobiledev

Credits
=======

Apple, iPhone, iPod, and iPod Touch are trademarks of Apple Inc.
libimobiledevice is an independent software library and has not been
authorized, sponsored, or otherwise approved by Apple Inc.

README Updated on:
	2015-01-28
