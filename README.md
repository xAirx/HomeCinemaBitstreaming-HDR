# HomeCinemaBitstreaming-HDR
## Download Links: 
     http://madvr.com/
     https://mpc-hc.org/downloads/
     https://github.com/Nevcairiel/LAVFilters/releases

## Guides: 

# IMPORTANT IN INTERNAL FILTERS IN MPC HC SET THE SPLITTER; AUDIO; VIDEO settings for LAV after setting  OUTPUT!

after that go to audiorenderer and enable bitstreaming!!
    
    https://forum.kodi.tv/showthread.php?tid=209596&pid=1843523#pid1843523
    https://forum.kodi.tv/showthread.php?tid=259188
    https://rubenalamina.mx/2014/03/04/bitstreaming-audio-with-media-player-classic-home-cinema/
    http://www.mediasmartserver.net/2010/02/02/guide-setting-up-bitstreaming-with-your-windows-7-htpc-part-i/
    
    !! not using KODI, but since documentation is pretty bad ill include them.
    
## Hardware:

    65x8500 Sony tv.
    Onkyo TX8505 7.1 reciever (does not support 4k passthrough so 2x hdmi cables are used, look below)
    Dali Suite 5.1 surround set + 2x dali trio for 7.1 (atmos).
     
     PC -> TV 
         HDMI cable from 1070 to TV (Video and HDR)


     PC -> reciever 
         HDMI cable from 1070 to reciever (Sound and Bitstreaming)


## Software Setup
    Nvidias own audio drivers
    MPC HC 32BIT (64bit cant do HDR passthrough to the TV)
    MADVR ( Program to run the HDR passthrough etc )
    Lav filters (Runs bitstreaming through MPC HC) "Dolby EX, Atmos DTS Master HD etc"




## Resolution and scaling up and down
   
   Everything related to trade quality for performance is OFF!
    
    Running 3840x2160p, native for UHD movies. no upscaling. (Lag with 1070 not strong enough for upscaling properly to      4096x2160?

    Upscaling settings "Not tested properly?"

    Chroma upscaling NGU very high
    Image upscaling Ngu Anti-alias very high, rest let madvr decide
    Image downscaling DXVA2
    Upscaling refinement Lumasharpen + adaptive + linear light
    Activate ringing filter 100%
    Anti ringing filter 


## Documentation

     Settings for each respectable program "included as image files"... 

## Watching movies
     
     If a pc monitor is connected, disconnect it so only the two cables for the home cinema resides.
     This is due to the fact that you use exclusive fullscreen forcing 24p for fluid playback, this bugs with a "second monitor"

     
### Monitor preferences.

     Cable from pc to reciever is seen as a monitor..
     Make sure that the "audio monitor" <- windows will see the hdmi cable for the sound as a monitor, 

     Make sure the hdmi cable going to the TV is the one set to preffered MAIN monitor in windows monitor settings. 
     
### Audio preferences

     Make sure the reciever is set as the DEFAULT audio speaker on both settings 
     Set configuration to 7.1 surround with full sound space on all speakers etc.
     Open MPC HC -> Drag video file into MPC HC, Voila!
