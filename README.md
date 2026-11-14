# DayZ HWID Spoofer

Download: soon

Clears a DayZ hardware ban signature from the PC.

## Components

1. Volume serial, system and secondary disks
2. Physical disk serial
3. MAC address, all adapters
4. SMBIOS UUID
5. Machine GUID
6. Temp, prefetch and recent list

## Usage

- right click, run as administrator
- component list: leave everything on
- Spoof, then reboot
- new Steam account, start DayZ

## Notes

The original values are backed up to `hwid_backup.json` before the first write and can be restored in one click. BattleEye builds up cached IDs in temp too, so do not skip the cleaner step.
