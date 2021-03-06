<<Turn On "WordWrap" option in the Edit menu if viewing by Notepad>>

WELCOME TO

                SYNCHROTRON RADIATION WORKSHOP (SRW)

CURRENT VERSION: SRW 3.95

====================================
WHAT SRW CAN DO? 

Current version of SRW enables the following:

- Near-field computation of Synchrotron Radiation generated by filament relativistic electron beam in magnetic field of arbitrary configuration. The effects of non-zero transverse emittance of electron beam can be computed in assumption of transversely uniform magnetic field.

- Propagation of Synchrotron Radiation from filament electron beam through simple optical elements like lenses, apertures and drift spaces. The Propagation is implemented in the frame of the Scalar Diffraction Theory using CPU-efficient methods of Fourier Optics.

- Fast computation of Undulator Radiation Spectra through a Slit for Finite-Emittance Electron Beam.

- Computation of Wiggler Radiation.

- Computation of Synchrotron Radiation Power Density.

- Estimation of Spectral Brightness of different sources.

- Simulation of SASE Wavefront Amplification (based on GENESIS 3D code developed at DESY; under testing).

====================================
CONFIGURATION REQUIRED

To use the SRW, you should have one of the following configurations:

- PowerMac with (at least) 32 M of memory, system 8.0 or later and a license of Igor Pro 3.1x/4.x (see http://www.wavemetrics.com).

- PC running Windows 95/98/NT4/2000/XP with (at least) 32 M of memory and a license of Igor Pro 3.1x/4.x.

The SR Propagation-related computations require 64 M of RAM installed in the computer and at least 30 M partitioned for the Igor Pro (Mac OS).

====================================
PREVIOUS VERSION SHOULD BE DE-INSTALLED

Before making any steps for installation of the new version, make sure that the previous version of SRW is completely de-installed from your system. This means that: 

Any aliases (shortcuts) of files and folders (or the files and folders itself) which have "SRW" in their names, should be removed from the following folders of your Igor Pro installation:
"Igor Pro Folder"
"Igor Pro Folder:Igor Extensions"
"Igor Pro Folder:Igor Help Files"
"Igor Pro Folder:Igor Procedures"

====================================
SRW INSTALLATION ON A POWER MACINTOSH

1. Download the archived SRW distribution (*.DMG) file for Macintosh.

2. "Mount" (decompress) the file. You should obtain a mounted disk folder named "SRW_Is_Here". Inside this folder, there should be the folder named "SRW".

3. Ensure de-installation of a previous version (see the details above).

4. Place the folder "SRW" as it is to the "Igor Pro Folder" where your license of the Igor Pro is installed.

5. Find the folder "SRW Procedures" inside the "SRW" folder. Make an alias of this folder and place the alias in "Igor Pro Folder:Igor Procedures".

6. Find the file "SRW.xop" inside the "SRW" folder. Make an alias of this file and place the alias in "Igor Pro Folder:Igor Extensions".

7. Find the file "SRW Macro Help.ifn" inside the "SRW:SRW Help" folder. Make an alias of this file and place the alias in "Igor Pro Folder:Igor Help Files".

8. If you intend to do Wavefront Propagation related computation with SRW, make sure that the memory partition for the Igor Pro is set to at least 50 MB.

9. (Re)Start Igor Pro. At the first start after the SRW installation, Igor may show a dialog box suggesting to compile the help file "SRW Macro Help.ifn". Choose to compile it. Finally, you should obtain inside Igor new menu item(s) named "SRW...".

====================================
SRW INSTALLATION ON A PC UNDER WINDOWS 95/98/NT4/2000/XP

1. Download the self-extracting SRW distribution executable file for Windows.

2. Quit Igor Pro, if it is running.

3. Run the self-extracting executable file. The installation utility will ask you to specify / confirm the location of Igor Pro, and will try to perform necessary actions for proper installation of SRW (i.e. create SRW folder inside the Igor Pro folder and create shortcuts to SRW files in Igor Pro sub-folders).

4. Start Igor Pro. At the first start after the SRW installation, Igor may show a dialog box suggesting to compile the help file "SRW Macro Help.ifn". Choose to compile it. Finally, you should obtain new menu item(s) named "SRW..." in the Igor menu.

====================================
GETTING STARTED

The first thing we recommend to do after the installation is to start Igor Pro and choose "Help->Introduction" in the menu SRW...

After this, one can try examples from the part of SRW of one's interest, e.g. "SRWE->Undulator->Help->Example: Spectrum through a Slit"

For convenience, the SRW help file "SRW Help.ifn" in the format of Igor Pro notebook can be printed out and used as a hard copy of SRW documentation.

====================================
COMPATIBILITY WITH PREVIOUS VERSIONS

SRW 3.x IS NOT fully compatible with previous versions. The names and arguments of some macro commands related to the SR computation were modified. However, since the principles of the code organization did not change, we hope that users can easily trace the changes and modify accordingly their own macro commands where SRW is used.

====================================
Authors:
Oleg CHUBAR (chubar@bnl.gov)
Pascal ELLEAUME (elleaume@esrf.fr)

December 2009