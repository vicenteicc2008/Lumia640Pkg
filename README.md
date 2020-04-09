# Lumia830Pkg
WIP Custom ARM UEFI firmware for Lumia 830, based on Lumia830Pkg by rickliu : https://github.com/rickliu2000/Lumia930Pkg

# Current Status
Edk2 boots correctly, but it is not capable of loading windows (just use unlocked stock uefi for that ). Linux is impossible right now, because there is no kernel with efistub and efiframebuffer support, it has to be backported and i am not able to do it.

# Thanks to : <br/>
 - Rick Liu for creating Lumia930Pkg<br/>
 - Konrad Dybcio for creating Lumia535Pkg, a guide how to port edk2 to lumias and for helping me out when I was stuck<br/>
 - Heathcliff74 for creating WPInternals<br/>
