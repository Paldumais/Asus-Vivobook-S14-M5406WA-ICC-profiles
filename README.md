ICC Color Profiles for Asus Vivobook S14 OLED (M5406WA)
This repository contains ICC (International Color Consortium) profiles for the Asus Vivobook S14 OLED (M5406WA) to improve color accuracy for creative and professional work.

🧐 Disclaimer
Use these profiles at your own risk. Display panels can have slight variations between units, so results may differ. For professional-grade accuracy, it is always recommended to calibrate your specific display with a colorimeter.

🎨 Profiles Included
M5406WA_1002_834C419D_CMDEF.icm : The default, out-of-the-box color profile extracted from the factory drivers.

S14.icm : From an article that calibrated it.

⚙️ Installation Instructions
Choose the guide for your operating system.

Windows
Open the Start Menu and search for Color Management, then open it.

In the Devices tab, select your laptop's display.

Check the box "Use my settings for this device".

Click the Add... button.

Click Browse... and navigate to the downloaded .icc or .icm profile file.

Select the new profile and click Set as Default Profile.

macOS
Copy the .icc profile file.

Open Finder and go to ~/Library/ColorSync/Profiles. (You can use Cmd+Shift+G and paste the path).

Paste the profile file into this folder.

Open System Settings > Displays.

Select the Color tab and choose the newly added profile from the list.

Linux (GNOME)
Open Settings and navigate to the Color panel.

Select your laptop's display.

Click Add Profile.

Select the downloaded .icc profile from the list or import it if it doesn't appear automatically.

Click Add to apply the profile.

🙌 Contributing
Contributions are welcome! If you have created a calibrated profile for this laptop model, please open a pull request. Kindly include details about your calibration hardware (e.g., SpyderX, Calibrite ColorChecker) and target settings (e.g., white point, gamma, brightness).

📜 License
This project is licensed under the MIT License.
