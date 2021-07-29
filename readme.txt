PSnoobSDK Installer by Alex Free

A quick, automatic, and easy unofficial installer for https://github.com/Lameguy64/PSn00bSDK. Designed for 64 bit Windows, Fedora, Ubuntu, and Debian systems.

- Installs any and all required build dependencies automatically using APT, DNF, or PACMAN in MSYS2.
- Builds GCC 7.4.0 and Binutils 2.31.1 for mips-unknown-elf ( these are the recommended versions by Lameguy64, the toolchain developer), then sets up the PSnoobSDK (with C++ support).
- Tests everything by building the PSnoobSDK examples.

Windows users: IMPORTANT - you must use the 'MSYS2 MinGW 64-bit' terminal to run ipsxsdk!
Simply run the 'ipsxsdk' script with (requires sudo if your not on Windows) in your Terminal, and let your machine finish running the script (may take awhile). 

After that, whenever you want to use the SDK first set your PATH with the command below:

export PATH=/usr/local/mipsel-unknown-elf/bin:/usr/local/mipsel-unknown-elf/psn00bsdk/tools/bin:$PATH

The GCC 7.4.0 and Binutils 2.31.1 toolchain is installed to /usr/local/mipsel-unknown-elf. The PSn00bSDK is at /usr/local/mipsel-unknown-elf/psn00bsdk, and examples are at /usr/local/mipsel-unknown-elf/psn00bsdk/examples.