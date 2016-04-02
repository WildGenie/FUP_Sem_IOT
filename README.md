# FUP_Sem_IOT
Functional Programming - Term Paper - IOT / Big Data

## Setup Raspbian on Micro SD Card

  0. Installation instructions: https://www.raspberrypi.org/documentation/installation/noobs.md
  1. Download NOOBS: https://www.raspberrypi.org/downloads
  2. Run
      ~~~
      sudo fdisk -l
      ~~~
  2. Insert Micro SD Card
  3. Find Device (Compare before and after insert)
     ~~~
     sudo fdisk -l
     ~~~
  4. Start fdisk
     ~~~
     sudo fdsik <PathToDevice>
     ~~~
  5. Delete existing partitions
     ~~~
     d
     ~~~
  6. Create new partition (use default values: p, 1, ...)
      ~~~
      n
      ~~~
  7. Verify partition
      ~~~
      p
      ~~~
  8.  Change partition type (Type: W95 FAT - b)
      ~~~
      t
      ~~~
  9.  Make partition 1 bootable
      ~~~
      a
      ~~~
  10. Write changes
      ~~~
      w
      ~~~
  11. Unmount device
  12. Format partition (Use path to device partition!)
      ~~~
      sudo mkfs.vfat <PathToDevicePartition>
      ~~~
  13. Remount device
  14. Unzip Noobs
  15. Copy contents of zip file to device
  16. Insert micro sd card into rapsberry pi and start

## Raspbian Setup
### WLAN

### Groove PI

### Mono / FSharp
