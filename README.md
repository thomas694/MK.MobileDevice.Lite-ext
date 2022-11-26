## Requirements

The iTunesMobileDevice.dll and dependent DLLs from the packages "Apple Application Support" and 
"Apple Mobile Device Support" (driver) are needed.

### How to download these packages?

Download an older iTunes Installer from the Internet, make sure to check the Digital Signature to be sure, 
and extract it with e.g. 7zip to get the MSI packages.
The upstream project used the iTunesMobileDevice.dll 757.3.2.1 which belongs to iTunes 12.1.1 from Jan 2015.
So you can either use the "Application Support" (3.1.2) and "Mobile Device Support" (8.1.1.3) installers from this iTunes version and 
use the DLLs in their respective folders.
Or you can use a newer version of the driver (Mobile Device Support, tested 14.1.0.35), but then you have to use the project's old iTunesMobileDevice.dll as newer 
versions of the driver don't contain that one any more.
<br>

## Changes
- enabled the Open methods
- added ReadAll method

<br><br>
(original)

---

This project is released to the public under the GPLv3 License.

MK MobileDevice Lite Library for interfacing with iOS Devices. 
Written in C#.NET, and compatiable with all iOS versions supported by iTunes. 
Requires Visual Studio and the .NET Framework to build; additionally, for
user support, requires Apple Application Support and Apple MobileDevice
Support. Prebuilt portable drivers and binaries are available in
Releases.

Created by MK Industries and ExaPhaser Industries.