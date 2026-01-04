## How to use

Build and flash it like any other XDKBuild image. However, don't expect a good experience unless you've got a Y1 GPU. The GPU patches we do for 1888 don't really translate to 1838 so well, it's actually more stable to NOT patch the GPU driver, but then you get poor performance and it's still a bit glitchy. If you're running on a rhea or zeus machine and see artifacts, your GPU isn't damaged. It's just that the kernel can't train the EDRAM correctly.

> [!IMPORTANT]
> Systems that use 16mb NAND chips must put the "1838-fs" folder on the root of the hard drive to be able to boot to dash or xshell. Unlike 17489, there's not enough room on the flash for a "base" set of files that can boot to a menu of some sort.
>
> In addition, kernel 1838 has zero support for retail formatted hard drives. It MUST be dev formatted. Xbox 360 neighborhood does work, so if you've got a dev formatted hard drive you can boot the system, and when it hangs at the end of the boot animation, copy the files over. Alternatively, you'll need to use a FATX injector program.


## Credits

- sk1080 for help getting this going
- XDKBuild VFuse patches and flag fixer: xvistaman2005
- 360hub Discord Server - https://discord.gg/z9r3HMUxp7
- RGLoader Discord Server - https://discord.gg/jTDT4rAh56

... and anyone else i may have forgotten