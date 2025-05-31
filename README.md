# Noise-Immune FAT32 File system
## Main goal
The main goal of this project is to make the FAT32 file system work in usage scenarios where `SEU` is common. </br>
Also this FS should work on embedded systems for my another project called [CDBMS](https://github.com/11adyy/AdyDBMS.PETPRJ).

## Current state
- Base implementation.
- Complete porting from `AdyOS` project.
- Implement noise-immune algorithms.
- Create format tool for creating modified FS on Flashs.
- Testing and comparing with other FS.

## References
FAT32 carcase was taken from my OS project [AdyOS](https://github.com/11adyy/AdyOS.PETPRJ). FS API itself was built with help of [OSDev](https://wiki.osdev.org/Expanded_Main_Page) tips, like this [topic](https://wiki.osdev.org/FAT).

