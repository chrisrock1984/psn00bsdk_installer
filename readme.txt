PSnoobSDK Installer by Alex Free

A quick, automatic, and easy unofficial installer for https://github.com/Lameguy64/PSn00bSDK.

Released into the Public Domain, see the file 'unlicense.txt'.

v1.0 - 5/2/21
- Installs all required dependencies automatically on Ubuntu/APT and Fedora/DNF based systems (tested on Fedora 33).
- Installs GCC 7.4.0 and Binutils 2.31.1 for mips-unknown-elf, then sets up the PSnoobSDK (with C++ support).
- Tests everything by building the PSnoobSDK examples.

Simply run the 'ipsxsdk' script with sudo in your Terminal, and let your machine finish running the script (may take awhile). 

After that, whenever you want to use the SDK first set your PATH with the command below:

export PATH=/usr/local/mipsel-unknown-elf/bin:/usr/local/mipsel-unknown-elf/psn00bsdk/tools/bin:$PATH

The GCC 7.4.0 and Binutils 2.31.1 toolchain is installed to /usr/local/mipsel-unknown-elf. The PSn00bSDK is at /usr/local/mipsel-unknown-elf/psn00bsdk, and examples are at /usr/local/mipsel-unknown-elf/psn00bsdk/examples.

