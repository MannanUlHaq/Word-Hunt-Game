Here are the instructions for running the Word Hunt game on DOSBox:

---

**Instructions for Running Word Hunt Game on DOSBox**

1. **Install DOSBox**: Download and install DOSBox from [the official website](https://www.dosbox.com/) if you haven't already.

2. **Prepare Your Files**: Ensure that `WordHunt.asm` and `Music.imf` are in a single folder on your computer, e.g., `C:\WordHuntGame`.

3. **Launch DOSBox**: Open DOSBox from your desktop or start menu.

4. **Mount the Directory**:
   - In the DOSBox command prompt, type the following command to mount the directory where your game files are located:
     ```
     mount c c:\WordHuntGame
     ```
   - Replace `c:\WordHuntGame` with the path to your folder if different.

5. **Change to the Mounted Directory**:
   - Type the command to switch to the mounted drive:
     ```
     c:
     ```

6. **Assemble and Run the Game**:
   - Assemble the `WordHunt.asm` file using an assembler like MASM (Microsoft Macro Assembler). If MASM is not already installed in your DOSBox setup, you'll need to obtain and configure it.
     ```
     masm WordHunt.asm
     ```
   - Link the assembled code:
     ```
     link WordHunt.obj
     ```
   - Run the game executable (e.g., `WordHunt.exe` or `WordHunt.com` if the assembler output was a COM file):
     ```
     WordHunt
     ```

7. **Enjoy the Game**: Follow on-screen instructions to play.
