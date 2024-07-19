# PET-A-V-Interface
And A/V Interface for Commodore PET computers
This is a <b>preliminary release</b>. The electronics is fully functional, but the test documentation might require some tweaking. 

The prupose of this project is providing video and audio (CB2) outputs for the Commodore PET computers. The non-CRTC machines generate video outputs, which can be mixed to resemble an NTSC video signal. The resulting signal can be displayed with NTSC monitors or suitable video to HDMI converters.

<img src="https://github.com/svenpetersen1965/PET-A-V-Interface/blob/main/Rev.%202/Pictures/3392_-_PETav_Framemeister.JPG" width="300" alt="CBM3016 with external display">

The internal video signal of the CRTC machines is not following any video standards. Thus it requires to modify the CRTC parameters in the EDIT ROM. The disavantage of these modiied settings is, that the internal monitor does not synchronize with them. It is mandatory to disconnect the video and the supply voltage for the monitor if run with PAL or NTSC parameters for more than just a few minutes.


