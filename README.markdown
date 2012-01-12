MicroModem
==========

License
-------

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.


This program will send a sms through the /dev/ttyUSBx
-----------------------------------------------------

Install the following package for building the debian package
-------------------------------------------------------------
	apt-get install build-essential devscripts debhelper

Howto build
-----------
	cd debian_package/micromodem-1.0
	debuild -us -uc

