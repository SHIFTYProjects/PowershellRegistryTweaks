# PowershellRegistryTweaks
Powershell Gui of some common registry tweaks.
**All Changes are reported to an output box.**
![image](https://user-images.githubusercontent.com/115837132/229208263-67111d78-f081-434d-9d89-adc106a189b1.png)



Current Registry Tweaks:

**Button 1.** DISM Repair: Deployment imaging and service management Tool
Generally for Windows images and VHD files, but has the ability to find problems with a local windows image as well.  It will copy down critical core files required to run from Microsoft and gather information, then upgrade or repairs any files that are corrupted or out-of-date.

**Button 2.** Run SFC - Runs the System File Checker tool
is best to run this after running the DISM Repair Tool.  This finds corrupt files or incorrect windows files by checking the hash of the file, then repairs them.

**Hiberboot Disable** - Disables deep hibernation.  This can help resolve a computer not going to sleep when closing the lid.  Or extremely slow shutdown times

**Hiberboot Enable** - Runs the reverse of the previous action.

**Disable WSUS** - Allows your computer to check for online windows updates, and not just use your companies WSUS server.  If you have a Group policy in place that allows your computer to only point to your local server for windows updates, this will only work until the GPO kicks back in.  (Depending on your heartbeat, around 15 minutes.)

**Enable WSUS** - Runs the reverse of the previous action.

**Disable Search Highlights** - Disables the ads in the search bar.

**Enable Highlights** - Runs the reverse of the previous action.

**AllowUpgrades** - Allows getting the Windows 11 Upgrade natively through Microsoft Windows Updates, even if the CPU and TPM is not listed as compatible or recommended.  This is a built in Registry key from Microsoft and is not considered a "Hack" to make it work.

**Dissallow Upgrades** - Runs the reverse of the previous action.

**Disable Bing** - Disables Bing in the search Bar.

**Enable Bing** - Runs the reverse of the previous action.

Get Serial Number - Gets the serial number (Service Tag) of the current machine.






