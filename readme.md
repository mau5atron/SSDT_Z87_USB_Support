This repo contains the SSDT-UIAC.aml, which is needed for USB support
on the Z87 Sabertooth Motherboard running macOS Sierra(10.12.X), 
macOS High Sierra(10.13.X), and macOS Mojave(10.14.X)

I used the template SSDT-UIAC-ALL.dsl and the extremely detailed guide
provided by RehabMan on the tonymacx86 forum. I have attached the
link below.  

https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/

MaciASL is used to compile the .dsl file to AML (ACPI Machine Language Binary)

The compiled .aml file that I have attached will need to be placed into 
the "EFI/Clover/ACPI/Patched" folder.

Reboot and all your USB ports should be accessible. 