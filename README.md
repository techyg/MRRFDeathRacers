# MRRF Death Racers
Repository containing useful information for MRRF Death Racers.

# *** Important **** Before you get started, things to know:

You are going to be printing A LOT. Depending on the # of printers you have, and how much you want to put on your build plate at a time, plan on taking 1-2 weeks to print parts, and quite possibly longer. 

Before starting to print it is a good idea to ensure that your printed parts are dimensionally accurate. There are some tolerances that will accomodate a little bit of under or over extrusion, but it's best to be as dimensionally accurate as possible to avoid issues. Here is a good article on calibrating your extrusion multiplier by Prusa:
https://help.prusa3d.com/article/extrusion-multiplier-calibration_2257

Also make sure your first layer z height is tuned sufficiently so you have good adhesion. You don't want to lose a print because it came lose. Consider using a brim on the larger parts with small surface contact to reduce curling.

If you really want your prints to look "amazing" also consider calibrating Pressure Advance (PA, on Klipper and RepRap Firmware) or Linear Advance (Marlin) as well as Input Shaper / Resonance Compensation. This can be a real rabbit hole, but the effort pays off. Here is a good resource for Klipper users that want to tune more advanced features:
https://github.com/AndrewEllis93/Print-Tuning-Guide

Your printer will need to be able to print the biggest file, which is called "MainFrame.STL". The dimensions of the largest file is: 237.9 (x) x 184.52 (y) x 47.34 (z) mm. You may be able to rotate this to fit your print bed.

You will also need to print TPU for the tracks. You can use a "Fast" tpu such as Sainsmart, or really anything with a Shore Hardness of 95A. Most printers (even bowden drives, like the Prusa Mini) will be able to print this without too much difficulty but it may require some profile tuning particularly around retraction and retraction speed.  Ask in the Facebook group.

There are a lot of different RC Radio options. I recommend the FlySky radio with the 6 channel receiver (which should be included). This is a basic radio but will work nicely with this build. 

Last but not least: PETG and TPU are both hygroscopic filaments, meaning they will suck in the humidity in the air. If you notice poor surface layer quality, bad layer or excessive stringing this is a sign that your filament may be "wet". You should dry your filament out. There are options for filament dryers and you can also use a food dehydrator. Plan on drying out for at least 2-3 hours at a temp of 125-130C. 

## *** Getting Started ***

# <b>Step 1. Join Michael Baddeley's Patreon to get STL files and overview info.</b> 

After joining, go this page and scroll to the bottom where it says "The link to my  Ondedrive is…"
https://www.patreon.com/mrbaddeley/membership

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

