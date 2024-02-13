# Tiva-C-Reset-Instructions
If you want to reset your Tiva C board or having trouble with the JTAG initialization failed error, download the folder and extract then follow the instructions to reset your board. 

# Tiva C LM Flash Programmer - Board Reset Instructions

If you encounter issues with your Tiva C board and the debugger cannot find it, you can try to reset the board using the following steps:

1. Download and install the LM Flash Programmer with the Tiva Launchpad option.

2. Ensure that Keil is not open.

3. Plug in your TM4C123 LaunchPad board.

4. Run the LM Flash Programmer application.

5. Select the "TM4C123 Launchpad" option.

6. Click on the "Other Utilities" tab.

7. Choose "Fury, DustDevil, TM4C123, and TM4C129" and click on "Unlock."

8. Confirm by clicking "Yes" (Note: TM4C123 does not have MAC addresses, while TM4C1294 does).

9. Follow the directions provided while keeping the reset button pressed.

10. Release the reset button and click "OK."

11. Power off and on the board, then click "OK" again.

    - Press and hold the reset button on the board.
    - Turn off the power.
    - Turn on the power.
    - Click "OK" while still holding the reset button.
    - Release the reset button.
    - Click "OK."
    - Power off the board.
    - Turn on the power.
    - Click "OK."

12. You should see a success message at the bottom.

13. Quit the LM Flash Programmer.

14. Congratulations, you have successfully reset your Tiva C board!

Note: This repository is provided as-is and does not constitute official TI specifications. Use it at your own risk.
