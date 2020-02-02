======================================================================
Renesas Electronics  Corporation                                     CP(N)
xHCI driver package for Linux Kernel 2.6.28
======================================================================

File: USB3-HOST-DRV-LNX-2_6_28-20120302.zip

  Original driver is xHCI driver supported in kernel 2.6.32.
  This driver package is customized for kernel 2.6.28.

----------------------------------------------------------------------
1.0 Directroy structure
----------------------------------------------------------------------
  USB3-HOST-DRV-LNX-2_6_28-20120302
   +- include
   |   +- linux			Header files
   |
   +- usb
       +- core			USB core driver files
       +- host			xHCI driver files
       +- storage		USB MSC related file
 
----------------------------------------------------------------------
2.0 How to use
----------------------------------------------------------------------
  - Copy(overwrite) "include" directory and "usb" directory to the following places
    in the target kernel(2.6.28) respectively.
  
     linux-2.6.28\include
     linux-2.6.28\drivers\usb
  
  - Kernel configuration
  
     Choose "m" or "y" at "CONFIG_USB_XHCI_HCD" in .config file.
     or at "xHCI HCD (USB 3.0) support (EXPERIMENTAL)" in the configuration menu window.

----------------------------------------------------------------------
3.0 LICENSING INFORMATION
----------------------------------------------------------------------
   This program is free software; you can redistribute it and/or modify it
   under the terms of the GNU General Public License as published by the
   Free Software Foundation; either version 2 of the License, or (at your
   option) any later version.
 
  This program is distributed in the hope that it will be useful, but
   WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
   or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License
   for more details.

    http://www.fsf.org/licenses/gpl.html 
 
   You should have received a copy of the GNU General Public License
   along with this program; if not, write to the Free Software Foundation,
   Inc., 675 Mass Ave, Cambridge, MA 02139, USA.
