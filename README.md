# Proxmark-Amiibo
Allow you to emulate the proxmark as amiibo very simply :)

## Installation
Just dowload the repo and copy it in the root of the Proxmark3.

## Usage
In the repo, you will find a file named `amiibo.txt`.  
So just open it, find the amiibo you want, for example i will take 8-Bit Link.  
<br>

In the file, you will find this :
```
*8-bit Link
hf mf eload u amiibo/BOTW/8-BITLink
hf 14a sim t 7 u 04B339DAE94C80
```
and with that, you just have to execute the two following commands.  
<br>

`hf mf eload u amiibo/BOTW/8-BITLink` will write the data on block (in the Proxmark)  
`hf 14a sim t 7 u 04B339DAE94C80` will emulate the amiibo (just press the Proxmark button to stop emulation)

## Precompiled emv
* **Zelda Breath Of The Wild**
    * 8-Bit Link
    * Archer Link
    * Bokolin
    * Link Ocarina Of Time
    * Toon Link
    * Toon Zelda
    * Wolf Link


