This is only for RedHat Linux machines
### Boot Steps in Linux
#### 1. The Computer BIOS(Basic Input Output System) performs POST(Power On Self Test).
#####Checks if all componets are working or not like hard disk etc..
#### 2. BIOS reads the MBR(Master Boot Record) 
#####MBR selects or calls the bootable device(GRUB-GRant Unified Bootloader)
#### 3. GRUB2 loads the kernal image.
#### 4. GRUB2 extracts the contents of the initramfs image.
#### 5. Kernal Loads driver modules from initramfs
#### 6. Kernal Starts the sustems first process, systemd
#### 7. Systemd process takes over and it reads all the configuration files and starts the services which are configured

###Summary
POST>MBR>GRUB2>Kernal>systemd
