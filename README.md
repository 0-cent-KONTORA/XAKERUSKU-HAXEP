https://simeononsecurity.com/github/optimizing-and-hardening-windows10-deployments/

Пидаркам, ой, хакеркам, пора бы знать...
Что тупой хак легко унять. Особенно когда цель беспантово понтаваться за государственные деньги.

https://github.com/pbatard/uefi-ntfs.git

Версия 4.14 (2026.04.30)
Windows User Experience improvements:
Add a Quality of Life option, to disable Teams, Outlook, Copilot and other Microsoft forced nuisances
Add a Silent installation option, that automatically, and WITHOUT PROMPT, installs Windows on the first detected disk
Add an option to copy SkuSiPolicy.p7b to the ESP on installation (please refer to KB5042562 for more info)
Add tooltips for all the dialog options
Add limited support for El-Torito UEFI image extraction (Mostly for Dell BIOS update ISOs)
Improve error report when the user tries to use an image that resides on the target drive
Improve the UEFI:NTFS partition label to make the install media more explicit during Windows Setup disk partitioning
Improve support for Bazzite and other Fedora derivatives that don't follow EFI conventions
Improve detection and exclusion of the new Bitdefender hidden VHDs
Improve reporting of GRUB and Isolinux MBRs
Fix potential errors during creation of Windows To Go media, due to the use of new versions of bcdboot
Fix errors with local accounts that start or end with whitespaces
