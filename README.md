# mayterm
MayTerm is a VT100 terminal emulator for the TRS-80 Model 4

While the TRS-80 model 4 would make a useful serial terminal for logging into a Linux serial console, there is no software that has good VT-100 support, support for special characters not on the Model 4 keyboard, and file transfer.

MayTerm is designed to be a lightweight and fast terminal emulator to allow a TRS-80 Model 4 to be used as a serial console to Linux hosts.   Functionalities that are not relevant for this (such as autodialing and modem control) are not part of the package.

As well, MayTerm is optimized for speed.  Given an upgraded serial board, the package will work at up to 115.2kbps.   The software should run reliably at 19.2kbps using the stock Model 4 hardware.

MayTerm supports XMODEM and YMODEM file transfers, allowing the user to transfer files between the TRS-80 and the Linux box easily.

Key product features:

* Strong VT-100 support allowing MayTerm to work well with Linux curses-based software
* Support for high-speed UARTS, reliable operation at 19.2kpbs using the stock serial board
* Default mappings to support characters not on TRS-80 keyboard (e.g. underscore)
* XMODEM/YMODEM file transfers
* 


  MayTerm is Copyright (c) 2015 Michael Maydaniuk

  This program is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this program.  If not, see <http://www.gnu.org/licenses/>.
