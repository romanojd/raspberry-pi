Create your own image
=======================

Here are the steps to create the image.

1. Begin by booting up the Raspberry Pi with a new Raspbian image.
2. Upon initial boot, it will enter "Raspberry Pi Software Configuration Tool (raspi-config)"
3. Select #4, "Internationalisation Options" and press the Enter key
4. Select "Change Locale" and press the Enter key
5. Uncheck "en_GB.UTF-8" and check "en_US.UTF-8" by pressing the Space key.  Then, press the Tab key to select "Ok" and press Enter.
6. In the "Configuring locales" window select the "en_US.UTF-8" locale and press the Enter key.
7. Back on the main screen, select "Internationalisation Options" again and then select "Change Timezone" and press the Enter key.
8. In the "Configuring tzdata" screen, select "US" and press the Enter key.
9. On the next screen, select "Eastern" and press the Enter key.
10. Back on the main screen, select "Internationalisation Options' again and then select "Change Keyboard Layout" and press the Enter key.
11. (I don't know if this needs to be set.  The default is "Generic 105-key (Intl) PC".)
12. On the next screen, select "Generic 105-key (Intl) PC" and press the Enter key.
13. On the next screen, select "Other" and press the Enter key.
14. Next, choose the country of origin for the keyboard.  Select "English (US)" and press the Enter key.
15. On the next screen, select "English (US)" and press the Enter key.
16. On the next screen, select "The default for the keyboard layout" and press the Enter key.
17. Set the compose key to "No compose key" and press the Enter key.
18. Set the behavior for Control+Alt+Backspace.  I set it to "No" and then press the Enter key.
19. Back on the main screen, press the Tab key to select "Finish" and press the Enter key.
20. Reboot the computer.
