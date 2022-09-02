# Installing the OPMID cluster
> [!warning]+ Check your odometer reading before you start!!
> Once disconnected, the odometer information cannot be retrieved.

> [!info]+
> - [Body panels](https://www.revzilla.com/oem/honda/2021-honda-trail-125-abs/body-cover?submodel=ct125aac)
> 
> Video guide:
> - [Youtube: OPMID Honda Trail 125 installation video](https://www.youtube.com/watch?v=idVKjywPmcU)

## Remove LID, BATTERY *R354* (GLOWING RED) (P/N 64460-K2E-T00ZB)
1. Push pin on the back left, 5mm hex key in the middle.
2. The back right of the panel has a small hook on it. Lift up from the left side, gently work things loose and then unhook it from the right rear.

## Remove GARNISH SET, AIR CLEANER *R354* (WL) (GLOWING RED) (P/N 83650-K2E-A00ZA)
1. Push pin on the back top, 5mm on front middle. If you don't remove the battery cover first, take care when releasing the top left side of the panel, there's an easy to snap tab there.

## Remove COVER SET, L. MAIN PIPE SIDE (TYPE1) (WL) (P/N 81140-K2E-T00ZC)
1. 5mm bolt lower front left, 5mm bolt center top, push pin center near the battery, 10mm socket for the flange bolt (P/N 95701-06012-00)

> [!info]- Reassembly note
The 5mm bolt on the lower front left is P/N 90132-KPP-T00, while the 5mm bolt in the center top is P/N 90132-MJE-D40 - these are different bolts, one has a longer shaft (longer shaft goes in to the top).

## Remove COVER, MAIN PIPE (LOWER) (P/N 64310-K2E-T00)
1. 4x Push pins

## Remove COVER (LOWER) *NHA40M* (MAT KRYPTON SILVER METALLIC) (P/N 64150-K2E-T00ZA) aka the bash plate.
1. 4x 5mm hex
Note: This wasn't strictly necessary, but it made accessing the oil temperature sensor easier and isn't very difficult to do.

## Remove the front most screw from the front right body panel COVER SET, R. MAIN PIPE SIDE (TYPE1) (WL) (P/N 81130-K2E-T00ZC)
1. 5mm hex key.
Note: This wasn't strictly necessary, but it made verifying the OPMID tacho spade connector was securely pushed in much easier.

At this point, the main body covers are off, except the right side.

## Remove RIM, HEADLIGHT (P/N 33101-K2E-T01) and HEADLIGHT UNIT (P/N 33110-K0F-T02)
1. This is part of the USB install but also used for the OPMID install. In the USB install video, the installer almost drops the headlight unit. Because of this, I taped it with some painter's tape first on the upper surface just in case, so if it did pop free it would just dangle from the tape.
2. Unscrew 2x screws on the 4 o'clock and 8 o'clock positions on the headlight. (P/N 91509-GE2-760) - JIS screwdriver
3. Release the headlight unit and unclip the plug at the back.

I also bought some OPMID screen protectors and installed them at the same time, because "right out of the box" is the cleanest this screen will ever be.

1. Remove the two screws holding the headlight unit to the left and right headlight brackets. (JIS screwdriver)
2. Inside there is a zip tie thing that's not exactly a zip tie holding all the cables bunched together. Check that your OPMID kit has a replacement for this before you cut it. Alternatively if you're creative with a knife, you can reuse it.
3. You can pass the screwdriver through the back of the headlight housing to access the screws on the instrumentation.
4. When installing the OPMID multimeter, the original speedometer used two washers on the left and right screws. The OPMID does not use those washers.
5. I couldn't reach the clip that holds the lowest point of the oil sensor cable without dropping the skidplate the first time. It's possible to reach it without doing that, but it's much easier to do it with the skidplate off.
6. The spade connector for the tacho was VERY stiff. If this falls out for any reason the engine will stop working. Make sure it's in completely (hence removing the front bolt to make sure it's done properly).

## Configure the OPMID cluster
It took me the longest time to figure out how to access the 1.4 menu for the odometer, etc. Ends up when you hold the A and B buttons together, if you hold them for 3s it does an adjust, and if you hold them for 6 seconds it enters the "bigger adjustment" mode (it will say ADJ at first, then FULL after 6s).
