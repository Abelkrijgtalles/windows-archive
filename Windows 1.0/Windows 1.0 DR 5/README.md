### Release notes

"DR5" is the earliest release known to still exist. If you think you have found an earlier build, please see our contributions section!

This was the 5th pre-release of Windows given to developers. It contained sample applications, some with source code. This requires [MS-DOS](/product/ms-dos) 2.x or 3.0 to run. A serial or bus mouse is also required.

CGA and Hercules graphics support was included in both.

### Installation instructions

PCem is known to run this. Configure PCem to emulate an "XT" style machine with a serial mouse. You will need to create a hard disk in PCem to use, 32 sectors, 16 heads and 30 cylinders will get you an 8MB hard disk. You will need to install DOS before Windows DR 5.

To switch from default CGA graphics to Hercules, do the following on command line:

*   path C:\\windows\\bin
*   cd C:\\Windows\\test
*   drivers HERCULES

You can swap back by running drivers IBMCOLOR to go back to CGA.

VMWare is not compatible with how this software uses CGA graphics. Neither VMWare nor Virtualbox emulate serial mice. We recommend that you do NOT use VMWare or Virtualbox. We recommend [PCEm](http://pcem-emulator.co.uk/) or [PCE](http://www.hampa.ch/pce/) instead.

**_Screenshots courtesy of [ToastyTech](http://toastytech.com/guis/win1984.html)_**