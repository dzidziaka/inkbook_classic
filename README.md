# inkbook_classic

My way to fix Inkbook Classic with broken flash:

I received a non-working Inkbook Classic reader from a friend.
All recipes aimed at putting the reader into bootloader mode failed in my case.
I bought the NAND Memory Programmer Lite v1.1 programmer (because my xgecu t-48 did not have a template for operating on H27UBG8T2BTR).
You need to unsolder the non-working H27UBG8T2BTR, clean the contents of the new one using NAND Lite and solder it into the reader.
After starting, the reader will enter bootloader mode and the firmware from the AV63L reader must be uploaded (search the Internet for AV63L Firmware, in my case it was AV63L Firmware 16/08/16 voor Auto Update). You have to do this because there is no official firmware image anywhere, only an update file.
After doing this, you will find the update files for the reader on elektroda.pl and you update them normally.