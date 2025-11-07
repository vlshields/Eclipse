# Step 1: The .love file

	a) First check the version number of the last .love file generated. We strictly use sementic versioning.
	Unless told otherwise, assume this is a minor patch. For example, if the last version was eclipse-v0.2.12.love,
	you should generate a love file called eclipse-v0.2.13.

	b) The love file should ONLY include files needed for the game to run. The only exception is license.txt.

	c) Now build the .love file

# Step 2: Our custom game Icon

	- **Win_64**:
		- The custom icon to use is eclipse.ico
		- Take a look at this page for instructions https://gamedev.stackexchange.com/questions/27341/how-do-i-change-a-l%c3%96ve2d-game-executables-icon/121947#121947,
		   but you will have to adjust since we are on Debian
	- **MacOS**:
     - The custom icon to use is eclipse_icon_mac.icns
     - Instructions are unclear, so please do extensive web research. We must get this correct

# Step 3: Build for MacOS

	a) Please see build_for_macos.txt
	b) Ensure step 2 is done properly
	c) ensure the .app bundle is named with the correct eclipse version

# Step 4: Build for Win_64

	a) Please see build_for_windows.txt
	b) Ensure step 2 is done properly
	c) ensure the .exe file is named with the correct eclipse version

