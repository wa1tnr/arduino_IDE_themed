Sun 14 Aug 21:41:12 UTC 2022

Arduino IDE themes

includes dracula theme - see distrib

The themes are .zip files placed in the sketchbook, under
a new directory you create (named 'theme').

In Debian Linux, that means by default, a theme named
'red_rover.zip' will be found at the pathname (directory
plus filename) of:

   /home/yourlogin/Arduino/theme/red_rover.zip

When unzipped, the files wind up in the very same directory
the command was given in.  For the sample file, named
yellow_comments.zip:

  mkdir /home/yourlogin/test_themes.d
  cd    /home/yourlogin/test_themes.d
  cp -p ~/Downloads/yellow_comments.zip .
  unzip yellow_comments.zip

  ls theme.txt  # verify it was just copied to the current directory
  ls ./syntax/default.xml # again, verify

This is just meant to show that it's the current directory that
gets the files when you unzip a theme .zip file.

Traditionally, when you unzip a file, a new directory is created,
and all files are unpacked to the newly-created directory.

Themes are not organized quite that way.

END.
