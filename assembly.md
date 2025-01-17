
## Oven Assembly method
- Get a convection toaster oven. Nothing fancy, it just has a fan inside for more even heating. Never use this oven for food.
  - [BLACK+DECKER TO3250XSB 8-Slice Extra Wide Convection Countertop Toaster Oven, Includes Bake Pan, Broil Rack & Toasting Rack, Stainless Steel/Black](https://www.amazon.com/BLACK-DECKER-TO3250XSB-Convection-Countertop/dp/B00LU2I428)
- Get a thermocouple thermometer. Make sure the probe and probe jacket can go to ~300C
  - [Digital Thermocouple Temperature Thermometer, PEAKMETER PM6501 K Type LCD Thermometer Testing Tool Celsius and Fahrenheit](https://www.amazon.com/Thermocouple-Temperature-Thermometer-PEAKMETER-Fahrenheit/dp/B08L11MMFM)
- Use Sn63/Pb37 no-clean, leaded, solder paste. Keep it in the refrigerator so it's nice and cold before you stencil it. (obvs don't get it near your food). Wash your hands well after.
  - [Chip Quik SMD291AX50T3 Solder Paste in jar 50g (T3) Sn63/Pb37 no clean](https://www.amazon.com/gp/product/B07BH5LP5G)
- Take your time to get the paste stenciled right. Don't be afraid to wipe it off with IPA and try again. The paste stencils better when it's cold.
- Use tweezers to put all of the parts on the pasted board. I like the curved Aven Technik 7-SA Tweezers. I have also been known to wear a dorky magnifier headset.
  - [Aven 18072ARS 7-SA Style Artis Tweezer, Black with Yellow Print](https://www.amazon.com/Aven-18072ARS-Style-Tweezer-Yellow/dp/B01D4R1OXW)
  - [Headband Magnifier Hands Free Jeweler Loupe Head Mount Magnifying Headset Visor Double Optical Glass 4 Replaceable Lenses for Reading,Repair(1.5X,2.0X,2.5X,3.5X)](https://www.amazon.com/Headband-Magnifier-Jeweler-Magnifying-Replaceable/dp/B08RYVH7DL)
- Put the board(s) in the toaster oven. I usually put them right on the wire rack, which is in the metal tray.
- Put the thermocouple inside the toaster oven. Close the door on the thermocouple wire so that it holds the end right above the PCB, inside the oven.
- Turn the oven on convection bake, medium setting. The convection fan in the toaster oven helps keep the temperature even through out the inside of the oven.
- Once the temp (as read off the thermocouple thermometer) gets to 140C, turn down the oven heat and try and keep it at 140-150C for 2 minutes. Open the door a little if it's getting to hot. This is the "Soak" phase
- After two minutes, turn the heat to high
- Once the temp reaches 200C start a timer for 30 seconds. Keep the temp between 200 and 220C for this phase. Usually you don't need to do anything. This is the "Reflow" phase. You should see all of the paste melt.
- After 30 seconds, turn off the toaster oven. open the door.
- Let the boards cool for a bit in the oven with the door open.
- Once cool to touch, inspect the boards with a microscope for dry pads and/or bridges. Depending on how well you did with stenciling there may be a few, especially on QFP packages. QFNs sometimes too. Fix these up with paste flux, solder braid and your soldering iron.
- If you have parts on both sides of the board, it's fine to just repeat the steps on the second side. The surface tension of the solder almost always keeps the parts from falling off while they are getting reflowed upside down. When you reflow the second side, make a little stand out of metal to keep the bottom side parts off the wire rack in the toaster oven.
  

## Hot air Assembly method
If you are comfortable with a hot air station and soldering iron it's possible to assemble the board with or without a stencil.
- pre-tin the solder pads with leaded solder (183C melting point). Solder wire or paste whatever is your preference
- use a good flux such as [Amtech](https://www.amazon.com/NC-559-V2-TF-no-clean-tacky-flux-hand-soldering/dp/B09Y7KF2TM) or similar

