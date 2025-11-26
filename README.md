# Hyperion MacroPad
A macro pad built for multi platform use with a screen to show mode changes and display graphics. I’m going to try and make it wireless as well.

# PCB Assembly & Firmware

## Materials
You will need **all components listed in the Bill of Materials (BOM)** to assemble this board.

---

## Assembly Steps

1. **Solder the KB2040**  
   Begin by attaching the KB2040 to the PCB.

2. **Solder all diodes**  
   Ensure *all diodes are facing the same direction* according to the silkscreen/polarity marking.

3. **Solder all switches**  
   Install and solder all mechanical switches.

4. **Solder remaining components**  
   Add the rest of the components from the BOM (connectors, headers, LEDs, etc.).

---

## Firmware

Firmware is provided in the **`hyperion`** file.  
It is a simple custom program created with help from ChatGPT.

To install:
1. Put the KB2040 into **UF2 bootloader mode**.  
2. Drag and drop the `hyperion` firmware file onto the device.  
3. The board will reboot automatically.

I have made a case but it is very bad i will be making a new case in a day or two just need to look around and see what looks good
