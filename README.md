# HomeCinemaBitstreaming-HDR

##Guides:
    
    https://forum.kodi.tv/showthread.php?tid=209596&pid=1843523#pid1843523
    https://forum.kodi.tv/showthread.php?tid=259188
    https://rubenalamina.mx/2014/03/04/bitstreaming-audio-with-media-player-classic-home-cinema/
    http://www.mediasmartserver.net/2010/02/02/guide-setting-up-bitstreaming-with-your-windows-7-htpc-part-i/
    
    !! not using KODI, but since documentation is pretty bad ill include them.
    
##Hardware:

    65x8500 Sony tv.
    Onkyo TX8505 7.1 reciever (does not support 4k passthrough so 2x hdmi cables are used, look below)
    Dali Suite 5.1 surround set + 2x dali trio for 7.1 (atmos).



##Software Setup
    Nvidias own audio drivers
    MPC HC 32BIT (64bit cant do HDR passthrough to the TV)
    MADVR ( Program to run the HDR passthrough etc )
    Lav filters (Runs bitstreaming through MPC HC) "Dolby EX, Atmos DTS Master HD etc"


##PC -> TV 
    HDMI cable from 1070 to TV (Video and HDR)
    

##PC -> reciever 
    HDMI cable from 1070 to reciever (Sound and Bitstreaming)



Settings for each respectable program "included as image files"... 


##Resolution and scaling up and down
   
   Everything related to trade quality for performance is OFF!
    
   # Running 3840x2160p, native for UHD movies. no upscaling. (Lag with 1070 not strong enough for upscaling properly to      4096x2160?

    Upscaling settings "Not tested properly?"

    Chroma upscaling NGU very high
    Image upscaling Ngu Anti-alias very high, rest let madvr decide
    Image downscaling DXVA2
    Upscaling refinement Lumasharpen + adaptive + linear light
    Activate ringing filter 100%
    Anti ringing filter 

