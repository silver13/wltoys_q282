
##**Firmware for q282 hexacopter ( rate / angle )**


###Radio protocol:
Current options are Stock q282 / H8 mini transmitter / devo, cg023 transmitter , CX-10 (later "blue" variant) and H7. Protocol is by default stock protocol, and can be changed in file config.h On stock tx 40 and 60 are level mode, 80 , 100 acro mode.

If using devo change to H8 protocol as it's a better protocol in several areas.

**video / pic functions not coded** (fpv will still work )

###Accelerometer calibration:
Move the pitch stick down 3 times within about 2 seconds. Needs to be done on a level surface. Saved so it only needs to be done once. You may need to use high rates in order to reach the treshold.

###Installation and Support
Currently this port is covered by the it's own thread on rcgroups.
http://www.rcgroups.com/forums/showthread.php?t=2634611#post34381034

###Wiki
http://sirdomsen.diskstation.me/dokuwiki/doku.php?id=start

###History:

### 16.12.16
* added stock protocol

### 30.11.16
* initial commit
