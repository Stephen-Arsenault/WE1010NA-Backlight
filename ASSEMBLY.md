# Installation

Installation is reasonably straight forward:
 1. With the WE 1010NA soldering control unit unplugged, remove 2 screws from the back. ([photo](images/disassemble_1.jpg?raw=true))
 2. Insert one wide spudger or two narrow spudgers to unfasten the rear clips. These clips are located directly behind the screw holes on the rear of the soldering control unit.
 3. Pivoting at the front of the unit, tilt the upper shell of the soldering control unit up and place it to the side. ([photo](images/disassemble_2.jpg?raw=true))
 4. Proceed to unclip the two connectors from the front of the soldering control unit. ([photo](images/disassemble_3.jpg?raw=true))
     - One has a plastic connector and is clipped to the control PCB.
     - The second is friction fit on the power switch.
 5. With the front face of the shell disconnected, proceed to remove the 4 T8 screws from the back of the control PCB. 
 6. Moving your attention to the backlight PCB, proceed to snip the "mouse bites" on the backlight holder PCB in order reduce the assembly to only the backlight PCB. ([photo](images/disassemble_4.jpg?raw=true))
 7. Place the backlight PCB such that the contacts labelled "5V" and "GND" are on the bottom of the LCD. (/images/disassemble_6.jpg?raw=true))
     It's beneficial to secure the PCB in place with a dab of CA glue or a glue gun. The attached photo shows capton tape but I found this created an undesireable color on the LCD.
8. Solder the two contacts: ([photo](images/disassemble_6.jpg?raw=true))
    - Solder a wire from the "5V" pad on the backlight PCB to the upper-left leg of N1.
    - Solder a wire from the "GND" pad on the backlight PCB to the right-most pin on the bottom right of the control PCB.
    - Optional: Apply solder to the bridges circled near U3 and U4 on the PCB. ([photo](images/optional_8.jpg?raw=true))
        - Without solder U3 and U4 are disabled
        - With solder U3 and U4 will light up.
        - This option is primarily for people concerned about overdrawing N1.
9. Trim the stand-off to the immediate bottom left of the LCD window so that it flush with the window. ([photo](images/disassemble_7.jpg?raw=true))
10. Proceed to reassemble your Weller WE 1010NA soldering control unit, beginning with step 5 and proceeding up.
    - I found it was easier to move the upper shell into the final position and then carefully tuck the front face back into place. YMMV
