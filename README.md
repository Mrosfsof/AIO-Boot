AIO Boot possesses unique, advanced and user-friendly features. Here is one of the many great features of AIO Boot.

- [AIO Boot](https://www.aioboot.com) Homepage
- [Download AIO Boot](https://www.aioboot.com/en/download/)
- [How to use AIO Boot?](https://www.aioboot.com/en/how-to-use/)

# Screenshots

![AIO Boot](https://www.aioboot.com/wp-content/uploads/2017/05/AIO-Boot-Grub2-Menu-English.jpg)

![AIO Boot](https://www.aioboot.com/wp-content/uploads/2017/05/AIOCreator.exe_-1.jpg)

# General

- Support boots in both UEFI and Legacy BIOS modes.
	- UEFI mode: Grub2, Clover and rEFInd.
	- Legacy mode: Grub2, Grub4Dos, Clover and Syslinux.
	- You can choose between Grub2 and Grub4Dos as the default boot loader. Only use Grub4Dos if your computer is not compatible with Grub2.
- Supports hard drive, external hard drive and USB, including SDcard.
- Boot into Legacy mode on the GPT hard disk.
- Secure Boot support via Shim and MokManager.
- Support booting into UEFI mode from Legacy mode via Clover regardless of your computer does not support UEFI mode.
- Boot via LAN via iPXE and Tiny PXE Server.
- Depending on the case, AIO Boot can be installed on multiple partitions:
	- **FAT32**:
		- You need to use FAT32 partitions to support booting in UEFI mode.
		- Some operating systems like Bitdefender, Fedora and Gentoo… do not support booting on NTFS partitions.
		- Ubuntu and Debian’s persistent mode is also not supported on NTFS partitions.
		- So we need to use the FAT32 format.
	- **NTFS**:
		- NTFS partitions can store files larger than 4GB. You can save large files such as backups, VHD files…
		- You can use resident mode larger than 4GB for Android-x86, Remix OS, Phoenix OS and WifiSlax 4.12.
		- So we need to use the NTFS format.
- Supports to integrate multiple Windows XP/7/8.1/10 installers into USB and HDD.
	- Support USB 3.0 driver for Windows 7 installer. This helps you to install Windows 7 using USB 3.0. If you use other software, you may get the error “`A required CD/DVD drive device driver is missing. If you have a driver floppy disk, CD, DVD, or USB flash drive, please insert it now.`“.
	- Support split ISO file into several if ISO file is larger than 4GB but you are using FAT32 format.
- Supports booting multiple operating systems in just one USB. Includes Linux, Android, Antivirus software, Disk utilities, Backup and recovery programs.
- Support booting WinPE and VHD.
- Supports persistent mode for many Linux, Android and anti-virus programs. This means that your data will be saved after each session.
- Supports identification and boot into the operating system already installed on your hard drive. Includes Windows, Linux, MacOS, FreeBSD and Android.
- Supports creating a partition image (**.PARTIMG**) from ISO file. Use this feature if AIO Boot does not support booting it.
- You can switch between the partitions where you have installed the AIO Boot. The menus and packages will be displayed correspondingly on that partition. From Grub2, press **y** to do this.
- Supports recovery of Windows bootloader in both UEFI and Legacy BIOS modes.
- You can change the language, background and font size in **Settings**.
- Password protection for the Grub2 menu.
	- Users can not boot, edit menus, or use the Grub2 command line before they enter the correct password.
	- The password is encrypted by PBKDF2 so no one will know the password you have set.
	- Anyone can change or remove the password if they have access to the Grub2 configuration files.

# AIO Boot Extractor

- Help you reformat USB to FAT32 before installing.
- Helps you create two FAT32 and NTFS partitions.
	- **FAT32**: support boots in UEFI mode.
	- **NTFS**: support for saving files larger than 4GB.

# Partition Image Mapper

- Support to create USB installed FreeBSD, TrueOS, Ubuntu Server, Debian, Kali Linux and even macOS without loss of data.
- Support boot multiple operating systems that AIO Boot can not support in the usual way.

# Download

You can [download AIO Boot](https://www.aioboot.com/en/download/) and experience now.