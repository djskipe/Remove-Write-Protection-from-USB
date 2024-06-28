# Remove-Write-Protection-from-USB

1) Open CMD with Administrator
2) Now write in sequences and press enter
3) diskpart
4) list disk
5) select disk 4 (4 is an example, you can check which number have the devices)
7) attributes disk clear readonly
After that you can close CMD

For check the result go to This PC --> Find the USB --> right click --> format --> format disk --> start

Now your USB are free from Write Protection

DISCLAIMER: THIS METHOD DELETE ALL YOUR FILES.
BACKUP ALL AND TRY THIS AFTER
