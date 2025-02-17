# bridgecommand AppImage

bridgecommand_AppImage how to build

See:
https://github.com/vpelss/bridgecommand_AppImage/blob/main/instructions.txt



Bridgecommand is naval ship simulator.

You can build it yourself here:

[https://smcameron.github.io/space-nerds-in-space/](https://github.com/bridgecommand/bc)

I have created a Linux AppImage for Bridgecommand for those who can't compile it.

My AppImage version is here: https://github.com/vpelss/Space-Nerds-In-Space-Appimage/releases/tag/download

Note: It is easiest to start in a Linux terminal. Making a launchable icon is possible, but will vary depending on your gui. 

- Download
- in a terminal run the following

```
chmod +x Bridge_Command-x86_64.AppImage
./Bridge_Command-x86_64.AppImage
```


Make a Desktop Icon

If you save Space_Nerds_in_Space-x86_64.AppImage in ~/AppImages/Space_Nerds_in_Space-x86_64.AppImage, then you would place a desttop file here: ~/.local/share/applications/snis.desktop and your snis.desktop file might contain the following. Also if you want the icon, download it also. Note that the paths MUST be absolute.

[Desktop Entry]
Name=Bridgecommand
GenericName=Bridgecommand
Comment=Networked naval bridge simulator
Exec=/home/{your login name}/AppImages/Bridge_Command-x86_64.AppImage
Icon=/home/{your login name}/AppImages/icon.svg
Terminal=true
Type=Application
Categories=Game;
Your game icon should now show in your gui menu under Game



