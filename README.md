# XU-Mini-M-MinUI-Single-Card-Setup-Mod

The SYSTEM file in this zip will enable you to **run MinUI from a single SD card on the XU Mini M**, which cannot be done using the official Moss-magicmini release. Please note that the tradeoff for this single card setup is the loss of the ability to share one MinUI card across multiple different devices.

## Changelog:

- v0.1.0 - Initial release
- v0.2.0 - Add back capability to use TF2 if present, so either 1-card OR 2-card setup can be used.

## Installation Instructions
1. **Download** the latest official releases of **[MOSS](https://github.com/shauninman/Moss-magicmini/releases/latest) and [MinUI](https://github.com/shauninman/MinUI/releases/latest)** from Shaun's GitHub, as well as my modified **[System.zip](https://github.com/ryanmsartor/XU-Mini-M-MinUI-Single-Card-Setup-Mod/releases/download/v0.1.0/SYSTEM.zip)**.

2. **Download** and install to your computer your preferred **software for flashing** bootable SD cards. I like [Raspberry Pi Imager](https://www.raspberrypi.com/software/), personally.

3. **Download** and install the free version of **[MiniTool Partition Wizard](https://cdn2.minitool.com/?p=pw&e=pw-free)** to your computer.

4. **Flash MOSS** to your SD card.

5. Next you will open **MiniTool Partition Wizard** to create the partition where MinUI and all your games will live.

    - Locate the SD card that has MOSS on it. 
![image](https://github.com/user-attachments/assets/9de5c70c-ef1b-44a5-9c0f-da9910792a62)

    - Right click the unallocated portion of the card and select **Create**.
![image](https://github.com/user-attachments/assets/77ea5555-9d35-45c3-9690-455d7359fa8e)

    - A warning window may pop up - click **Yes** to continue. 
![image](https://github.com/user-attachments/assets/9d454c99-c208-4f5b-a5bd-99612d53795a)

    - In the next window, set the File System to **FAT32**. Click **OK**.
![image](https://github.com/user-attachments/assets/c60b5ffd-d38f-40e2-8759-5bc7cf215757)

    - At the bottom left of MiniTool, you should now see one operation pending. **Click Apply.**
![image](https://github.com/user-attachments/assets/9e37961b-00d7-45f6-945e-a538387542bf)

    - Click **Yes** to apply your changes.
![image](https://github.com/user-attachments/assets/a5777814-cf1d-4b78-bf62-af7d95fac6c3)

    - Once it has successfully applied the changes, thus creating the partition, you can click **OK**, then you may **exit out of MiniTool.**
![image](https://github.com/user-attachments/assets/d75c72b7-5ee2-42b0-af87-3f25427b107c)

6. In your computer's **File Explorer**, you should now see both a **MOSS** partition, and an empty **USB Drive partition**. Note: the empty partition may be called something else, depending on your OS. 
![image](https://github.com/user-attachments/assets/1778a323-6587-4c48-a5c8-4655c68bb228)

7. **Open the MOSS partition, and delete the file called SYSTEM.** Extract the **SYSTEM.zip** from this release page, and copy and **paste this new SYSTEM file onto your MOSS partition**, where the old one was.
![image](https://github.com/user-attachments/assets/635b362c-806d-4bbc-b914-b45071a4d2c0)

8. Open the empty partition that you created on your card and install MinUI to that location, **following the instructions from the official base release zip's readme**.
![image](https://github.com/user-attachments/assets/2ac62f52-2aa4-4abf-969a-db445b691a16)

9. Eject your SD card from your computer, and insert it into the lefthand slot of your XU Mini M, then boot the device. **Congrats, you are now running a single card setup of MinUI!**
