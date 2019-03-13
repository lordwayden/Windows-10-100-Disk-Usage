# Windows-10-100-Disk-Usage

Disable Windows Search
  On your keyboard, press the Windows X. Shell (Admin). 
   net.exe stop "Windows search"
   net.exe stop superfetch
    chkdsk.exe /f /r

Windows logo key + R 
  services.msc
  Locate Windows Search and disable it!
  
  temp
  Delete all files
  
Reset Virtual Memory
  Go to the Advanced System Settings (press Windows key and Pause/ Break key at the same time).
  Go to the Advanced tab, then click Settings
  Go to the Advanced tab again, and choose Change
  Ensure the Automatically manage paging file size for all drives checkbox is NOT ticked
  Set Recommended as it is and set Maximum size. It's RAM.
  
  Source https://www.drivereasy.com/knowledge/100-disk-usage-windows-10-fixed/
