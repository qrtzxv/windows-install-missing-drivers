# windows-install-missing-drivers
A guide for missing drivers during a Windows OS install

<br>

Where did this start ??

\> This started when I was trying to install windows 10 but the installation was unable to detect any storage drives. This may apply to other drivers. 

\> Better thank SmallFlaccid for making the installaion of their OS ""User Friendly"". 

<br><br>

## Steps
1. Download the .exe installation file for the driver(s)
2. Extract (yes, Extract. or Unzip) the file somewhere easy to remember
3. Copy the Extracted folder to the root of the install media; __whatever you named your install drive__, *not* in the UEFI_NTFS partition

Now boot into your install drive and run the installation. 
During installation, navigate to the folder that you copied when asked for the drives.

<br><br>

(re)sources :: 
> https://answers.microsoft.com/en-us/windows/forum/all/ssd-not-recognized-by-windows-10-11-installer/f993e54f-dc9b-4c0b-b5b0-6e9d3c7e1c1d
>
> https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/windows-setup-edition-configuration-and-product-id-files--eicfg-and-pidtxt?view=windows-11
>
> https://answers.microsoft.com/en-us/windows/forum/all/windows-10-usb-install-media-driver-missing/e6f91d6c-3b51-42f5-a4cc-580a469b7d9c
> 
> -------
