# bios-roms

Made with
- 8388608 : flashrom -p linux_spi:dev=/dev/spidev0.0,spispeed=1500 -c "W25Q64.V" -r factory1.rom
- 4194304 : flashrom -p linux_spi:dev=/dev/spidev0.0,spispeed=1500 -c "W25Q32.V" -r factory1.rom

laptop | bios version | size | in-circuit?
---|---|---|---
Sony Vaio SVT1311M1RS | Insyde Corp. R0220E4, 11.09.2012, SMBIOS 2.7 | 8388608 | yes
Sony Vaio SVE1112M1RB or SVE111B11V | R0120D8 InsydeH2O | 4194304 | yes
Lenovo R500 | BIOS 78CN10WW(V1.07) 07/04/2013 | 8388608 | no
Lenovo G505 | | 4194304 | yes
Lenovo ThinkPad T420 - original | | 8388608 | yes
Lenovo ThinkPad T420 - Chinese | | 8388608 | yes
