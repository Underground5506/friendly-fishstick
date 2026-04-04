#Problem fixer database

## No sound (System does not detect speaker or microphone)

Solutions that I found:

##- Windows 10 and 11: 
Reinstall the audio drivers by going to the device manufacturer's website.

##- Linux based OS: 
Reinstall ALSA and PipeWire by doing:
sudo apt install --reinstall pipewire alsa-base alsa-utils

##- Hardware (BIOS): 
Reboot the PC using the on/off button (Hard reset). When the manufacturer logo appears, spam ESC or F2 to enter BIOS. Go to the Security or Peripherals tab and check if there is a "PCIE Lock" or "Audio Interface Lock". If yes, switch it to Unlock. Save and Exit (F10).

# What OS affected: 
Windows 10, Windows 11 and Linux based OS
