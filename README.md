# AesmlyOS
A 16-bit assembly operating system for x86 PCs, based on the MikeOS project.
----------------------------------------------------------------------------
The goal of AesmlyOS is to provide a simple and lightweight operating system for x86 PCs. 

The operating system is written in assembly language, which allows for maximum control and efficiency. It takes advantage of the 16-bit architecture of x86 processors, allowing it to run on older hardware.

AesmlyOS includes a range of basic features, such as a commandline and a text editor. It also includes some additional features, like an ASCII art program, and some games (hangman, pong and more!).

AesmlyOS is small and fast, with a minimal footprint. It can be loaded into memory from a bootable disk or USB drive, and it does not require a separate installation process.

Note: AesmlyOS is a hobby project by one developer, it's perpose is to make a better looking version of MikeOS. As such, updates may be random.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Building, Installing And Modifying AesmlyOS
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
##### Installing
1. Download the latest release from the realeses section of the github page.
2. Use a program like Etcher or follow the MikeOS user instructions at [here](https://mikeos.sourceforge.net/handbook-user.html) to etch it using dd (Linux) to a usb stick.
3. Shutdown your computer and reboot while smacking the one-time boot menu button (f12 for me).
4. Use the arrow keys to select boot from usb.
5. Enjoy your new operating system.
   ** You can also run AesmlyOS in a virtual machine (Any development since MikeOS where done in a virtual machine).
##### Building and Modifying
** Requires: NASM assembler, dosfstools package, 'mkisofs' utility and root access.

To build Aesmly unpack the zip or 
``` 
git clone https://github.com/Colpr/aesmlyOS.git
```
Then:
1. Navigate to the main folder, example: `aesmlyos`.
2. Compile Aesmly using:
```
./build-linux.sh
```
3. Follow the Installation instructions above.
