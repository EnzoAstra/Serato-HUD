# DJ-HUD
Instructions for adding a low-latency information display to all modern Digital DJing softwares such as Serato DJ Pro + Lite, Rekordbox, Mixxx

DJ HUD
A Mixer 'Mounted' Secondary Screen for DJ Software
Problem:
1) Equipment and Peripherals providing Serato Track Info and Waveforms having a short lifespan before getting pulled off the market (eg:Numark Dashboard, Rane 72 mixer), and built in options running a premium (Pioneer DJ DJM-S11; Rane Performer, System One mixdeck controllers)

2) Secondary Screen needs to be low latency or it will be useless at best, a detriment at worst.

My Solution:

Hardware:
11.3 inch 1920X440 Bar Monitor  - ~100USD https://www.aliexpress.com/item/1005006321903854.html?spm=a2g0o.order_list.order_list_main.71.5f5518021BQbXf

a 1920x720 bar monitor can also be used if you use additional Serato extensions, but for just track + waveforms 1920x440 works best visually with my tests (performance of response/latency should be unaffected)

Software:
NDI Tools
https://ndi.video/tools/

.
NDI Tools are a set of programs that allow for low latency video and audio sharing usually between multiple computers, but for this it will all be local, we’ll be using 2 programs

NDI Screen Capture – To Capture the top of the Serato App

NDI Studio Monitor – To display the screen capture onto our secondary monitor
