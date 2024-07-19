# CrowdStrike BSOD Fixer

## Fix for the 7/19/2024 CrowdStrike global outage.  REQUIRES ADMIN - NOT TESTED ON ACTUAL CRASHED HARDWARE.

## Will not delete any files other than below.

- C:\Windows\System32\Drivers\CrowdStrike\C00000291*.sys

- C:\Windows\System\System32\Drivers\CrowdStrike\C00000291*.sys

# Directions:

- Clone this repo using ```git clone``` or click the green "Code" button above and "Download as ZIP"

- Place this on a USB stick or some other storage medium to plug into an affected computer

- Reboot BSOD-affected computer into safe mode

- Run the Run.lnk file, (or run Fix.bat as administrator)

- Reboot the computer.

Do not be worried if it says "The system cannot find the path specified." once, that is because it will attempt to delete a file path supplied by Microsoft as the fix, the filepath Microsoft supplied seems to be incorrect though.
