# OpenCore OpenCanopy Themes
**THEME: CPK**


This theme is intended for **OpenCore 0.7.3 and 0.7.4** (updated to comply with the Flavours system).

https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Flavours.md



 

![](CPK/Screenshots/Screenshot_Background_1/12205357.png)

![](CPK/Screenshots/Screenshot_Background_1/12205402.png)

![](CPK/Screenshots/Screenshot_Background_1/12205421.png)

![](CPK/Screenshots/Screenshot_Background_1/12205427.png)

![](CPK/Screenshots/Screenshot_Background_1/12205439.png)

![](CPK/Screenshots/Screenshot_Background_1/12205448.png)





**HOW TO INSTALL:** 

1 - Download the **CPK** file under **Releases**.

2 - Unzip it.

3 - Mount your EFI partition.

4 - DO A **FULL BACKUP OF YOUR EFI FOLDER**. Preferably in an external medium.

5 - Go to EFI/OC/Resources/**Image**.

6 - Create a folder named **canemdormienti**.

7 - Inside that folder create another one named **CPK**.

8 - It now looks like this:


 - /EFI/OC/Resources/Image/Acidanthera/Chardonnay
 - /EFI/OC/Resources/Image/Acidanthera/GoldenGate
 - /EFI/OC/Resources/Image/Acidanthera/Syrah
 - /EFI/OC/Resources/Image/**canemdormienti/CPK**
 


![](CPK/Previews-png/Desktop-Screenshots-Examples/ScreenShot_3.png)



9 - Copy the .icns from the extracted directory CPK/Resources/**Image** and paste it in the newly created **CPK** folder. Those are the basic system icns for the theme to work properly.


![](CPK/Previews-png/Desktop-Screenshots-Examples/ScreenShot_4.png)

![](CPK/Previews-png/Desktop-Screenshots-Examples/ScreenShot_5.png)


10 - Now, open your Config.plist. Search and edit this parameters:

**Misc** 
    >**Boot**

- LauncherOption >> String >> **Full**
- LauncherPath >> String >> **Default**
- PickerAttributes >> Number >> **144**
- PickerMode >> String >> **External**
- PickerVariant >> String >> **canemdormienti\CPK**
- ShowPicker >> Boolean >> **True**


![](CPK/Previews-png/Previews-Config.plist/ScreenShot_2.png)


11 - Save the Config.plist

12 - For those who want the Boot Chime activated:

- https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html#setting-up-boot-chime-with-audiodxe

- There is a file named **OCEFIAudio_VoiceOver_Boot.mp3** inside CPK/Resources/**Audio**, copy it and paste/replace into this directory EFI/OC/Resources/**Audio**


![](CPK/Previews-png/Desktop-Screenshots-Examples/ScreenShot_6.png)


13 - In separate folders, are also included icns for use with the Flavours system (macOS versions, Recovery, Time Machine, GNU/Linux Distros, Windows versions). There are, too; icns to change the appearance of the USB installers and Backgrounds for different display resolutions. 


![](CPK/Previews-png/Desktop-Screenshots-Examples/ScreenShot_2.png)


Some of the backgrounds were taken from here:

 - https://www.this-is-cool.co.uk/josh-marlow-sci-fi-environment-artist/
 - https://www.this-is-cool.co.uk/the-futuristic-3d-tech-art-of-amin-akhshi/
 - https://www.this-is-cool.co.uk/the-science-fiction-art-of-andrew-collins/
 - https://www.this-is-cool.co.uk/the-stunning-sci-fi-art-of-stefan-morrell/

  >>The COPYRIGHT and CREDITS belongs to the respective owners/designers of the logos, pictures, background images, icons and other elements used in this themes. I' am NOT affiliated in any way with "CD Projekt Red" or his subsidiaries.

Thank's to https://github.com/chris1111 for OpenCanopy-Generator and Background-Resizer. Those save A LOT of work...
