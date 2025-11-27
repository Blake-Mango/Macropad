# Hyperion MacroPad
A macro pad built for multi platform use with a screen to show mode changes and display graphics. I’m going to try and make it wireless as well.

# PCB Assembly & Firmware

## Materials
You will need **all components listed in the Bill of Materials (BOM)** to assemble this board. + the 3d printed case.(currrently pretty bad) 
<img width="651" height="425" alt="Screenshot 2025-11-27 015338" src="https://github.com/user-attachments/assets/63c078a4-65c4-4450-963f-3c04fab646bf" />

### Heres what the PCB should look like
<img width="1344" height="724" alt="image" src="https://github.com/user-attachments/assets/e1973fcb-5f4b-4169-b055-bce628bd9a85" /> <img width="1200" height="708" alt="image" src="https://github.com/user-attachments/assets/e50b2a68-f1f8-4c48-8773-9dd61e1138da" />



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
