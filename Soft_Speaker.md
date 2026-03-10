# Soft Speaker


***NOTE: This is an experimental technology. Soft speakers will not match the sound quality of conventional speakers — they are best understood as a creative and educational exploration of how sound, textiles and electronics intersect.***

----

## UNDERSTANDING SOFT SPEAKERS

A speaker makes sound because an electromagnet (the embroidered coil) is mounted to a membrane (the fabric) with a permanent magnet close by. 

When electricity flows through a wire, it creates a magnetic field around that wire. The more you coil the wire up, the stronger that magnetic field gets.

If you hold a magnet near the coil and then switch the electricity on, the two magnetic fields either attract or repel each other — just like two fridge magnets.

Audio isn't a steady current, it's a rapidly alternating one. The current constantly flips direction, which means your coil's magnetic field constantly flips too — attracting and repelling the permanent magnet many times per second.

That back-and-forth physical movement pushes air, and pushed air is sound.

----
## HARDWARE

- Wire or conductive thread

- Fabric: Woven muslin — recommended for beginners, light and tightly woven, vibrates well
Alternatives: silk (more tactile sensation), canvas or leather (deeper sound). Avoid loose weaves or stretchy fabrics — harder to work with and absorb vibration.

- Magnet 2cm diameter or larger — the stronger the magnet, the louder the speaker.

- Audio cable: 3.5mm stereo jack

- Amplifier (optional but recommended). You will need a Power Supply for the amplifier.

- Multimeter (for testing)

----
## KEY DESIGN PARAMETERS

The following design parameters will affect the efficiency and sound quality of your speaker. 

- **Type of Fabric:** The stiffness of the material you embroider on affects the volume of your speaker too. Too soft will absorb the vibration, too stiff will prevent the fabric to move... Different fabrics can produce different qualities of sound. Testing is advised.

- **Wire or conductive thread:** Both will work, which one to use will depend on what matters most to you:
    
    - Wire: Best sound. Has very low resistance (you can have meters and meters of coil), which allows more spiral turns = stronger magnetic field = louder speaker. Look for "38 AWG magnet wire".
 
    - Conductive Thread: Washable, ideal for wearables, textile-like results, but quieter sound. Look for thread with resistance of 2Ω/m or lower.
    

- **Length of Thread/Wire (resistance per meter):** The total length of your conductive thread determines the resistance of your coil, which affects the sound signal. If adding a sound amplifier, the thread/wire resistance must be at least equal to or higher than the amplifier requirement. To calculate how much thread you need, divide your target resistance (small amplifiers often 4-8Ω) by the resistance per meter of your thread: Thread length = target resistance (Ω) ÷ resistance per meter (Ω/m). Find more about this in the tutorials that follow. 

- **Diameter of the spiral pattern:** The diameter of your spiral determines how many turns you can fit. More turns in a smaller area = stronger magnetic field = louder speaker. 

- **Embroidery Stitch Type & Embroidery Pattern Design:** A basic running stitch works well for beginners — keep stitches small and consistent. A couch stitch (where a non-conductive thread holds the conductive thread flat) works better for thicker wire. Avoid large uneven stitches as they make the coil inconsistent and harder to control. The spiral pattern should be as tight as possible without turns touching. 

- **Strength of the Magnet:** The louder your speaker, the stronger the magnet you need. Neodymium magnets work best. The magnet should be at least 2cm in diameter and suspended just above or behind the fabric without touching it — if it touches, it restricts the fabric's vibration and dampens the sound. Note that strong magnets can be hazardous near pacemakers or metallic objects, which is an important consideration for wearable designs.

- **Audio input**: Try out sound/music with lots of bass, lots of vocals, and different ranges of tones in combination with your fabric and coil choices to see how it changes the sound.

----
## LIMITATIONS

- Sound is audible in proximity of centimeters. Adding an sound amplifier is advised to get higher sound volume. 
  
- If the magnet is too strong, it can become a hazard to the user if they wear metallic objects like earrings.

- Small neodymium magnets can be dangerous near pacemakers, so this should be considered carefully in wearable contexts.

-----
## TUTORIALS

The following list of tutorials cover the making of "soft speakers". Each of them uses different techniques and provide different tips. They provide complementary guidance: 

[Embroidered Fabric Speaker](https://www.instructables.com/Embroidered-Fabric-Speaker/)

[Headband Headphones](https://www.instructables.com/Headband-Headphones/?utm_source=Pinterest&utm_medium=organic)

[MAKE: Sew Wearable Soft Speakers](https://makezine.com/projects/soft-speakers/)

[Soft Speakers case studies](https://www.youtube.com/watch?v=BmzgDkjxWbU)

-----
## Art Examples

[Listening to the Leaves](https://technolojie.com/listening-to-the-leaves/)

----
## Tips:

MATERIAL CHECK: Some copper wire has an insulating coating — this is fine and won't affect the magnetic field. However you must sand or scrape the wire ends before connecting to your amplifier or circuit to have a proper connection. Use a multimeter and test continuity. 

NO SPEAKER POLARITY: There's no true "positive" or "negative" wire terminals for the speaker. Both will work as positive or negative.

EMBROIDING TIPS: As you are sewing your coil from center to edge, you want the conductive thread to come as close as possible to the previous turn without touching it. 

AVOID SHORT CUTS: If your coil has touching turns, it will short-circuit. This reduces the resistance of your coil (which can damage your amplifier), and weakens the magnetic field — because electricity takes a shortcut instead of being forced to travel around every turn. Each turn adds to the magnetic field, so missing turns means a weaker signal and quieter sound. Use a multimeter to measure resistance across your coil — it should read a few ohms at least. If it reads 0Ω or very close, your turns are touching somewhere."

MAGNET SHORT CUTTING: Since the magnet is conductive it could short out your speaker's coils. You can also put a piece of fabric in between the magnet and the coil to isolate it. For your final design you will want to mount your magnet(s) in the center of the coil without having them directly connected to the membrane.

COIL TURNS: The more turns your can make your coil (without touching points) into a small area, the louder your fabric speaker will be.

AMPLIFIER WARNING: It’s really important to ensure your speaker does not have less resistance than the amplifier requires, or you can risk damaging your audio devices.

----

## HOW TO USE A MULTIMETER

TO TEST CONTINUITY:

- Set your multimeter to the continuity symbol (usually looks like a sound wave or arrow pointing to a line)

- Touch both probes to each end of your wire or thread

- If it beeps, current is flowing — your material is conductive

- No beep means the material is not conducting, or your connection is broken

TO TEST WIRE/THREAD RESISTANCE PER METER:

- Cut exactly 1 meter of your thread or wire

- Set your multimeter dial to the 200Ω range

- Touch one probe to each end

- The number displayed is your resistance per meter — use this in your formula

TO TEST YOUR FINISHED COIL:

- Keep the multimeter on the 200Ω range

- Touch one probe to the very start of your spiral, the other to the very end

- Should read at or above your amplifier's minimum (typically 4Ω)

- If it reads near 0Ω, your turns are touching somewhere — you have a short circuit

----

## Further Learning

[Conductive Materials](https://github.com/kingston-hackSpace/Conductive_materials)


