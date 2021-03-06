# MRRF Death Racers
Repository containing useful information for MRRF Death Racers.

# *** Important **** Before you get started, things to know:

You are going to be printing A LOT. Depending on the # of printers you have, and how much you want to put on your build plate at a time, plan on taking 1-2 weeks to print parts, and quite possibly longer. 

Before starting to print it is a good idea to ensure that your printed parts are dimensionally accurate. There are some tolerances that will accomodate a little bit of under or over extrusion, but it's best to be as dimensionally accurate as possible to avoid issues. Here is a good article on calibrating your extrusion multiplier by Prusa:
https://help.prusa3d.com/article/extrusion-multiplier-calibration_2257

Also make sure your first layer z height is tuned sufficiently so you have good adhesion. You don't want to lose a print because it came loose. Consider using a brim on the larger parts with small surface contact to reduce curling.

If you really want your prints to look "amazing" also consider calibrating Pressure Advance (PA, on Klipper and RepRap Firmware) or Linear Advance (Marlin) as well as Input Shaper / Resonance Compensation. This can be a real rabbit hole, but the effort pays off. Here is a good resource for Klipper users that want to tune more advanced features:
https://github.com/AndrewEllis93/Print-Tuning-Guide

Your printer will need to be able to print the biggest file, which is called "MainFrame.STL". The dimensions of the largest file is: 237.9 (x) x 184.52 (y) x 47.34 (z) mm. You may be able to rotate this to fit your print bed. 

You will also need to print TPU for the tracks. You can use a "Fast" tpu such as Sainsmart, or really anything with a Shore Hardness of 95A. Most printers (even bowden drives, like the Prusa Mini) will be able to print this without too much difficulty but it may require some profile tuning particularly around retraction and retraction speed.  Ask in the Facebook group.

There are a lot of different RC Radio options. I recommend the FlySky radio with the 6 channel receiver (which should be included). This is a basic radio but will work nicely with this build and included in the BOM below. 

Last but not least: PETG and TPU are both hygroscopic filaments, meaning they will suck in the humidity in the air. If you notice poor surface layer quality, bad layer or excessive stringing this is a sign that your filament may be "wet". You should dry your filament out. There are options for filament dryers and you can also use a food dehydrator. Plan on drying out for at least 2-3 hours at a temp of 125-130C. 

## *** Getting Started ***

# <b>Step 1. Join Michael Baddeley's Patreon to get STL files and overview info.</b> 

After joining, go this page and scroll to the bottom where it says "The link to my  Ondedrive is???"
https://www.patreon.com/mrbaddeley/membership

# Planning Colors

Depending on your budget and how adventerous you are feeling, you may want to plan your colors. The BOM recommends 2 rolls of PETG but you may want more than that. For example, 1 color for the drive parts, another for the front frame and bike seat, a 3rd color for "trim" as well as a 4th color for the Rider and possibly even more for accents. There is a link to the Fusion 360 files in the Instructions, which are located in the Onedrive folder. You will need a password to access it which is also in the instructions. This is useful if you want to browse to see what the part names are, and how things go together, and example colors of different parts. You can click on the part to see the name.  The Fusion 360 file has 4 different colors as of the present time of writing.

Additional 3d printed files not in the Onedrive. Note: These may require a Facebook log in.

Blank side plate:
https://www.facebook.com/download/3419853774930152/Blank%20Side%20Plate%20Option.stl?av=570342076&eav=AfZNd2QF1y4ff55FL8Okbn5YhkQt-acM1M5XMSw63-DsLTQFdwjmCWFdhU0GB7Lq5So&paipv=0&hash=AcoL9mXFBv-cLIA-3AU&__cft__[0]=AZVck69kDNAClarfsAUE460D-dK5t1sHkS_k4UYZw7vFuXa4zHiz58pAUdedtUspZUCa93kNoU8vuSsv7ibVDILkg9jZKHHYJ385bv_mn2BR3T9a9YR0QapjfFjIqUD19R0LytrUz_fDpauwaT9inX8qbla5pV2rKW5rhJ1Kb-rz3VNY6IbCnSapaSplPVeHwII5g-dvd0g3doR-bnOspG2T&__tn__=H-R

3D Printing Nerd Side Plate:
https://www.facebook.com/download/1267429367127478/3DprintingNerd.stl?av=570342076&eav=AfYbXdrg756xKTd13p4MpS9W7h0dGt1HgohSjYj8qzJNzoM0SWD1c84d5e_L2pYqQ7Y&paipv=0&hash=Acrwg3kO534-KVf7PYU&__cft__[0]=AZVtagHHSABhSGggIyOj_UyBcAqIPwESP22waT8Jg1VQHSLy2IcPYgknPPPTbod-3X1IHC0EzrQ4SoTkAAiw9aPiUX2t3mGZpmLUCVwzcko51MOTTndRZnGjYyJz1qsKVEhJt04bd9vGhvA53wuWeAZmcybPsgrnEVPMfdihqkFZUjZhAIvY8CeFlnfd-hZmcsWqmTtbxJCUVytSPmx_N3Yl&__tn__=H-R

Polymaker Side Plate:
https://www.facebook.com/download/591689459241460/Polymaker%20_%20SidePlate.stl?av=570342076&eav=AfYqRaAjXAt9-dKzwiOoh3t8yHMnS2ZeYTcZEubKjMXUPvvuSQBKaAXnvTH7gLr3yRo&paipv=0&hash=AcpUPY9W3UU5aSn-9ik&__cft__[0]=AZXuHFQJoCWSf_E4bXoCHWTgsm9mnkWLuRY9qnF0PGvWp5bCCEhZ610XxR3IPNecfu6rDLzGz-oAlK5hUmNJzbT0XCJyt0qC02LMvv5LyRFInS6UAOl9iTvoLFwOgJnCfYbiwXP20aqQ_D3H36L9CSVS0vg708vSXaVssXrCb_49jCNEIoeezQ61mw5qhd_uL36z-Soyf49cLHkEqjM9z4L2&__tn__=H-R

# <b>Step 2. Watch the Build Video.</b> 

Detailed Build Video:

https://www.youtube.com/watch?v=eL_KUPhg6RI

Death Racers as seen at MRRF (Where it all started!):

https://www.youtube.com/watch?v=PqwJk8rcAIU&t=0s

I recommend using the instructions in the Onedrive along side with the video. It provides all the screw sizes that you will need for each step. Please note that you will need counter sunk (also called flat head) m3 screws, see the BOM for an example kit.

# <b>Step 3. Order from the BOM </b>

This BOM is based on Sam Prentice's spreadsheet here:
https://onedrive.live.com/?cid=e0240f3f28326535&id=E0240F3F28326535%21318&authkey=%21AEoHqmPpPdt6YsE![image](https://user-images.githubusercontent.com/22796810/177439761-63208eed-d35c-4b13-82d8-b14b2e9d7edf.png)

Plan to budget around $300-$500 for this build. You will be on the lower end of that budget if you already have supplies (filament, RC Radio, spare wiring, etc.).

# <b>United States BOM</b>

* 2 Rolls of PLA, PLA+ or PETG (PETG Recommended)  - I used GreenGate PETG but any will do
* 1 Roll of TPU - I used Sainsmart TPU (95A) https://www.amazon.com/SainSmart-Flexible-Printing-Filament-Dimensional/dp/B00TI3JUTM/
* Pololu 10:1 1000rpm Geared Motor: https://www.pololu.com/product/4748
* Wire for battery leads: https://www.amazon.com/dp/B01KCPL3GC/
* 4S Lipo Battery: https://www.amazon.com/dp/B08SW2ZXJW
* Battery Charger: https://www.amazon.com/dp/B07ZD6PZWN/?coliid=I2I6M64YM9S1ZJ
* Assortment of flat head (countersunk) screws: https://www.amazon.com/dp/B09BRDLF6N
* Cytron 10Amp 7v-30v DC Motor Driver: https://www.amazon.com/dp/B08XTZ9KPS
* 6802RS Ball Bearings: https://www.amazon.com/dp/B086CYRBSZ
* 4pcs 6mm Flange Coupling Connectors: https://www.amazon.com/dp/B08334N261
* 5pcs MG90S Servo Motor: https://www.amazon.com/dp/B09BV5D7MD
* 25KG Digital Servo: https://www.amazon.com/dp/B08ZSPVKQ3
* Servo Extension Wire: https://www.amazon.com/dp/B07R14N3Z6
* Servo Extension Y Connectors: https://www.amazon.com/dp/B07PHDYZXN
* Toggle Switch: https://www.amazon.com/dp/B07T6XWZKN
* 100pcs 2mm Rod Axle: https://www.amazon.com/dp/B07D2WSF29 
* XT60 Connectors for Battery: https://www.amazon.com/dp/B07VRZR5TL/
* FlySky 6 Channel Radio with Reciever: https://www.amazon.com/dp/B0744DPPL8/
* Recommended: Lipo Battery Low Voltage Alarm: https://www.amazon.com/dp/B08VW92TYD/
* 6mm Bar : (TBD) For Bludgers

# <b>Step 4. Print your parts!</b>

<b>Recommended Print Settings</b>

I suggest .20 layer height for all printed parts for a good balance of strength and print time.

Drive: 20-30% infill, 5 walls - You want these parts sturdy/strong. 

Everything else: You're probably ok dropping the infill and walls to conserve filament, but I went with the same settings as the Drive section.

TPU Tracks: 5% infill, 3 walls - Go slow on perimiters (no more than 15 mm/sec) otherwise you may have cooling issues.

# <b>Step 5. Wiring</b>

Wiring Diagram (From Sam Prentice on Facebook):
https://www.facebook.com/photo/?fbid=10159945649265867&set=gm.441888027512518

# Assembly Tips

If you have difficulty fitting your battery in, you can use a small file, exacto knife, or deburring tool to trim plastic off the "lip" at the back of the frame. I ended up shaving off about 1.5-2mm of plastic in order to get my battery to fit, as it was otherwise too tight to go in.

Take your time during assembly. The manual tells you which size screw to use for the most part, other times you might need to just figure it out. You will need an m3 driver, and most screws can/should be done by hand. There a few parts (ex. 50mm screws that go into the wheels) that I'd recommend using a very low powered drill otherwise your hand is going to get very sore. 

# RC Controller Tips

I used the FlySky FS-I6 radio. In order to bind the radio, place the bind plug on the receiver, power it up from the board (connected to RX 1). Power on your radio while holding the bind button. You should hear a beep and see RX Bound immediately. If it's not binding, go into your radio setup (hold down the OK button) and make sure that AFHDS is enabled. 

Bind procedure here:
https://www.youtube.com/watch?v=xRmlNQ3M3zE

Setting up a new model:
https://www.youtube.com/watch?v=9-Z0rTVEkHI

# RC Controller / Receiver Troubleshooting

The wiring diagram assumes that you are using channel 1 for steering (left/right) and channel 2 for forward/reverse. This is the default order for many radios that are using mode 2, including the FlySky FS-i6. Since these radios are designed for airplanes/drones by default, channel 1 will be referred to as "pitch" (or Aileron) and channel 2 "roll" (or Elevator). This channel mapping is commonly referred to as "AETR" order (Aileron, Elevator, Throttle, Rudder). In the AETR channel map, the first two channels map to the gimbal on the right hand side of the radio which is what is intended for this project. Other radios, such as the FrSky Taranis and Spektrum DX6 may different channel orders (TAER), so you will either have to remap the channels in the radio or plug a different channel (for example, 2 and 3) into the motor control board for control of the tank. 

If one of your directions are reversed (forward goes reverse, or left goes right), you'll need to reverse the channels. For the FlySky FS-i6 this can be done fairly easy by going into the controller setup menu by holding "OK" and then browsing to Function Setup, and then choose "reverse". Toggle the channel you need to reverse by hitting the up/down button. Long press "Cancel" to save (hold for maybe 5 seconds).

Here is a video that shows how to reverse channels (FlySky FS-i6):
https://www.youtube.com/watch?v=-xNJZd9CGNg&t=60s

If your controller is going forward and reverse when you intend to go sideways or backwards, the easiest way to fix that is by swapping the channels that connect from the RC receiver to the control board.

If you run into issues configuring your Radio, ask in the Deathracer Facebook group.
