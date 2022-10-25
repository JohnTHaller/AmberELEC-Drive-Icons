# AmberELEC-Drive-Icons
This set of files will allow you to have custom names and icons for your AmberELEC GAMES and AMBRELC microSD partitions.

# How To Install

1. Download the AmberELEC Icons vX.X.zip file and extract it somewhere on your PC.
2. Plug your microSD with the current AmbderELEC installed on it into your PC via a card reader or adapter.
3. Copy the autorun.inf and autorun.ico files within the AMBRELC folder to your AMBRELC partition's root directory.
4. Copy the autorun.inf and autorun.ico files within the GAMES folder to your GAMES partition's root directory.
5. Safely eject your drive via Windows and then remove it.
6. Plug your drive back in and you should see the changes.

# How To Customize

You can change the icon to any ICO file you'd like. Just replace the autorun.ico file in the root and then eject and re-insert. It's best if it has all the standard Windows sizes (256px, 48px, 32px, 16px, etc) so it will show up properly within Windows Explorer in all views.

You can rename the drive to anything you'd like by editting the autorun.inf file in your favorite text editor. Change the entry next to Label= to be the name you'd like your drive to appear as. Then eject and re-insert to see the changes. Note that this will not change the actual partition names seen by AmberELEC/Linux nor shown within Drive Propterties' General tab. DO NOT change the actual partition names as this will cause isssues with AmberELEC.

# COPYRIGHT

The AmberELEC autorun.ico logo icon within the AMBRELC directory is copyrighted by and a trademark of the AmberELEC project. The icon file itself was created by John T. Haller and based on AmberELEC's SVG logo files. Copyright is assigned to AmberELEC by John T. Haller on 2022-10-24.

The microSD autorun.ico icon within the GAMES directory is copyright John T. Haller and was created due to a lack of photo-realistic microSD icons with open source licenses. It has been released under the GPL 2 and later versions. The AmberELEC icon added to this logo is separately copyrighted by the AmberELEC project.

John T. Haller -  https://johnhaller.com/

# LICENSE

GPL v2 and later. See License.txt
