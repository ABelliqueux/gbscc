# gbscc - gbscontrol control

A python command line utility to send commands to a wifi enabled gbs-control over http.

Your gbscontrol instance has to be reachable over http at `gbscontrol.local` .

Alternatively, you can edit the `GBSCONTROL_ADDRESS` variable to reflect your network configuration.

## Usage : 

  `gbscc /COMMAND`

## Available commands :

	Presets :

		Video modes:

		 /720P   1280x720

		 /960P   1280x960

		 /1024P  1280x1024

		 /1080P  1920x1080

		 /SD     NTSC : 720x480 / PAL : 768x576 

		 /15K    15Khz Scale Down 

		 /PASS   Pass Through 

	Slots :

		 /1      Load Slot 1

		 /2      Load Slot 2

		 /3      Load Slot 3

		 /4      Load Slot 4

		 /5      Load Slot 5

		 /6      Load Slot 6

		 /7      Load Slot 7

		 /8      Load Slot 8

		 /9      Load Slot 9

		 /LOAD   Load Custom preset

		 /SAVE   Save Custom preset

	System :

		 /RESET  Reset the GBS

	Enhancements:

		 /SCNLN   240P Scanlines

		 /LINEF   Line filter

		 /PEAK    Peaking

		 /STEPR   Step response

		 /SCNLS   Scanline strength

	Preferences:

		 /MATCH   Matched presets

		 /FULLH   Full height

		 /UPSCL   Low Res: Use Upscaling

		 /60H     Force 60hz

		 /ADCCAL  ADC calibration

		 /FRMTL   FrameTime lock

		 /SWLCK   Switch lock method

		 /RGBC    RGBHV/Component Toggle

		 /MAD     Deinterlace motion adaptive

		 /BOB     Deinterlace bob

	Development:

		 /FREEZ   Freeze capture

		 /MBL     Move picture left (memory blank)

		 /MBR     Move picture right (memory blank)

		 /HSL     Horizontal Sync Left

		 /HSR     Horizontal Sync Right

		 /INFO    Print infos

		 /TIMI    Get video timings

		 /CLKR    Cycle Sdram clock speed

		 /RSTC    Reset chip

		 /INVS    Invert sync

		 /PLLD    PLL divider++

		 /DEBG    Debug view

		 /ADCF    ADC filter

		 /OVRS    Oversampling

		 /HTOTU   HTotal++ 

		 /HTOTD   HTotal-- 

		 /SNCHT   Resynch HTotal

		 /RSTS    Reset sync processor

		 /SNAP    Snap to 50/60hz

		 /SNCW    Syncwatcher

		 /OTA     Enable OTA update

		 /IFAO    IF auto offset

		 /SOGL    SOG Level --

	Picture Control:

		Move picture:

		 /MVUP    Up

		 /MVDN    Down

		 /MVL     Left

		 /MVR     Right

		Scaling:

		 /HORZU   Horizontal +

		 /HORZD   Horizontal -

		 /VERTU   Vertical + 

		 /VERTD   Vertical -

		Border masking:

		 /BMHU    Horizontal +

		 /BMHD    Horizontal -

		 /BMVU    Vertical +

		 /BMVD    Vertical -

		Gain:

		 /GAINU   Gain +

		 /GAIND   Gain -

		 /AUTOG   Auto Gain Adjust Toggle

