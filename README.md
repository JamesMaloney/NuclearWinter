# NuclearWinter
OpenCore configuration for macOS Mojave on ASUS TUF Z390-PLUS GAMING (WI-FI) and Intel® Core™ i9-9900K

Quickly made and basic configuration I made in my spare time to run macOS Mojave on my main hardware. I chose Mojave since it's the last version that runs 32 bit mac-only apps. Compatible with the following configuration:

- Motherboard: ASUS TUF Z390-PLUS GAMING (WI-FI)
- CPU: Intel® Core™ i9-9900K
- iGPU: Intel® UHD Graphics 630
- dGPU: None (should be compatible with some AMD GPUs out of the box)
- Storage: Sabrent SSD M.2 NVMe PCIe
- WiFi and Bluetooth: Included

AirDrop, sleep and boot chime don't work for my setup, so I just disabled them.

Feel free to use, though if you do:

- Generate a new SMBIOS using https://github.com/corpnewt/GenSMBIOS
- Open the config.plist with any editor
- Fill in "MLB", "ROM", "SystemSerialNumber" and "SystemUUID" under "PlatformInfo"

"Patrolling the Mojave Almost Makes You Wish For a Nuclear Winter"
