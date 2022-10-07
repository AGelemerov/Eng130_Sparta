# Installation - Windows 10
1. Go to https://www.python.org/downloads/
2. Download the installer for whichever operating system you have.
3. Follow the installation wizard until you get to a menu where you have to select checkboxes.
4. Make sure "Association with .py files" is checked.
5. Make sure "Add python to PATH variable" is also checked.

# How to check if you installed Python correctly
1. Press Windows key and type "cmd" and press Enter
2. In the console type the following:
  - python --version
3. If python is not recognised as a command, you may need to restart your computer (because of the PATH variable)
4. Try to check again, if it does not work, refer to "Correcting PATH variable" section

# Correcting PATH variable
1. Press Windows key and search for "environment"
2. A prompt to select "Edit environment variables" should come up, click it
3. A small window appears which has different options listed, click on the "Environment Variables..." one
4. Another window should appear with two big boxes
5. The top one is for the current account you are logged in with, the bottom one for the entire system
6. Alter the top one preferably but if this does not work, try the following steps for the system box
7. Find the variable called "Path" and select it
8. Click on "Edit..."
9. Press "New" on the top right
10. Copy and paste the "bin" folder of where you installed Python (e.g. C/USER/PROGRAM_FILES/PYTHON/BIN) to the new variable you are creating
11. Click OK
12. Restart your computer and this time it should work (unless condition at stage 6 is met, then alter the system box)
