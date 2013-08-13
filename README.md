Open Ephys for 32-bit Windows
=======================

This repository contains a 32-bit Windows binary file for the Open Ephys GUI. It will run on 64-bit Windows as well. However, the Opal Kelly drivers necessary to use the Open Ephys acquisition board or Intan RHD2000 evaluation board aren't
compatible with Windows 8. Don't you just love Windows?

For the source code, see http://github.com/open-ephys/GUI.

This software is still being developed, so we can't guarantee that anything will work as expected. Don't use it for mission-critical data acquisition unless you've thoroughly tested all the features you'll need.

Installation instructions
-------------------------------

1. Download the files from http://open-ephys.org/gui. Or, if you have the [Windows GitHub client](http://windows.github.com/) installed on your machine, you can use the "Clone in Desktop" button on
[this page](https://github.com/open-ephys-GUI-binaries/linux-64). The advantage of cloning is that you'll be able to easily keep track of any updates by periodically syncing with the master branch. 
Otherwise, you'll have to manually download the software (or build it from source) whenever something changes.

2. Drag the "linux-64-master" (downloaded version) to the location of your choice and rename it "Open Ephys." If you used GitHub for Windows to clone the repository, we recommend leaving it in the "GitHub" folder.

3. Run the "FrontPanelUSB-DriverOnly-Win-x4.0.8" application to install the Opal Kelly drivers (which don't work on Windows 8). This step is optional if you won't be using the GUI with the Open Ephys acquisition board or Intan RHD2000 eval board.

4. Double-click the "open-ephys" application file to run the software.

If you run into problems
-------------------------------

1. READ THE [GUI WIKI](https://github.com/open-ephys/GUI/wiki). There's a lot of useful information on the "Tutorial" and "User documentation" pages.

2. If you can consistently replicate the problem, [submit an issue](https://github.com/open-ephys/GUI/issues). You'll need a GitHub account for this, but it's worth signing up for one anyway.

3. As a last resort, [get in touch with us directly](http://open-ephys.org/contact)

