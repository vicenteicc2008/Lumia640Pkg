# Lumia640Pkg
WIP Custom ARM UEFI firmware for Lumia 640 LTE but should work on 3G version, based on Lumia830Pkg by Dominduchami : https://github.com/Dominduchami/Lumia830Pkg

# Current Status
Edk2 boots correctly, but it is not capable of loading windows (just use unlocked stock uefi for that). 
Linux boots with patches created by Bartosz Dudziak (https://patchwork.kernel.org/project/linux-arm-msm/list/?series=&submitter=193041&state=*&q=&archive=both&delegate=) and a simple dts (only UART and EMMC is enabled for now, display works via efiframebuffer).
A partially working kernel is available here : https://github.com/Mainline4Lumia/linux/tree/msm8x26

# Thanks to : <br/>
 - Rick Liu for creating Lumia930Pkg<br/>
 - Dominduchami for creating Lumia830Pkg<br/>
 - Konrad Dybcio for creating Lumia535Pkg, a guide how to port edk2 to lumias and for helping me out when I was stuck<br/>
 - Gustave Monce for telling me that rpmdxe driver is needed to bring up regulators on linux and helping me to get it to work<br/> 
 - Imbushuo for creating BootShim and helping with memory adresses for rpmdxe<br/>
 - Heathcliff74 for creating WPInternals<br/>
 - Credits to Anuel AA for the cover of the album "Real Hasta La Muerte" and I decided to use it as a Boot Logo because I like Anuel AA
