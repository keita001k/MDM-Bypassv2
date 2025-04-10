Bypass-MDM for MacOS 💻![mdm-screen](https://github.com/user-attachments/assets/29b45eb4-2a83-4c18-bc3f-4d6a6286bf84)

mdm-screen

Prerequisites ⚠️
It is advised to erase the hard-drive prior to starting.
It is advised to re-install MacOS using an external flash drive.
Device language needs to be set to English, it can be changed afterwards.
Follow steps below to bypass MDM setup during a fresh installation of MacOS
Upon arriving to the setup stage of forced MDM enrollement:

Long press Power button to forcefully shut down your Mac.

Hold the power button to start your Mac & boot into recovery mode.

a. Apple-based Mac: Hold Power button.
b. Intel-based Mac: Hold CMD + R during boot.

Connect to WiFi to activate your Mac.

Enter Recovery Mode & Open Safari.

Navigate to https://www.github.com/assafdori/bypass-mdm

Copy the script below:

curl https://raw.githubusercontent.com/assafdori/bypass-mdm/main/bypass-mdm.sh -o bypass-mdm.sh && chmod +x ./bypass-mdm.sh && ./bypass-mdm.sh
Launch Terminal (Utilities > Terminal).

Paste (CMD + V) and Run the script (ENTER).

Input 1 for Autobypass.

Press Enter to leave the default username 'Apple'.

Press Enter to leave the default password '1234'.

Wait for the script to finish & Reboot your Mac.

Sign in with user (Apple) & password (1234)

Skip all setup (Apple ID, Siri, Touch ID, Location Services)

Once on the desktop navigate to System Settings > Users and Groups, and create your real Admin account.

Log out of the Apple profile, and sign in into your real profile.

Feel free set up properly now (Apple ID, Siri, Touch ID, Location Services).

Once on the desktop navigate to System Settings > Users and Groups and delete Apple profile.

Congratulations, you're MDM free! 💫

Although it's virtually impossible to catch that you've removed the MDM (because it wasn't even configured), be aware that the serial number of the laptop will still be shown in the inventory system of your company. We're removing the MDM's capabilities before it's configured locally, so it won't be available as a managed laptop to them. Use with caution. Probably a good idea to have a valid excuse as well.
