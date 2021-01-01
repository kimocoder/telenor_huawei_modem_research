# telenor_huawei_modem_research
Research of the Huawei B818-260 used by many operators worldwide



* I'm interested in the firmware files first off, where to find them and how they
  are after some reversing / fiddling with it.

 - We know the update server is "http://update.hicloud.com:8180" from the dump from bwlow
   https://gist.github.com/ValdikSS/f0f0d5ab9444b74ffedb7a41572bbbb5

 [ Started a scan of directories and endings (bruteforceing names/dirs) - "dirsearch" running ]
 
 - Enumerating hostname (sniffing dns pointers) is available
   In Wireshark, set it up to do so, them login to modem and
   push "Check for updates" will reveal the update server.


















