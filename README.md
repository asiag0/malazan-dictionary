# malazan-dictionary
quick reference dictionary in stardict and kobo formats.

this is a dictionary project for the Malazan series of books.  the intent of
this project is a quick reference usable on the Kobo ereaders, and as stardict
format for use with most other digital dictionary programs.

there may be some spoilers, this is unavoidable.  most major spoilers have been
removed from the definitions.

the source material was the wiki at http://malazan.fandom.com/, some personal
notes, and other input.  suggestions and criticisms are always welcome.


files:
  - malazan.xdxf (xdxf format) - this is the master file, easiest to edit as it's
    basically xml, and very versatile (some features of the standard I plan to
    exploit in the future)
  - malazan.kobo.zip - this is the file used on the kobo ereaders.
  - malazan.ifo (stardict format - you'll need the .idx, .dict, and .syn files
    too)

installation on kobo devices:
  - enable/download a translation dictionary (on the device settings) that you do
  not plan on using.
  - connect your device to a computer via usb.
  - using a file manager, browse to the dictionary directory, and make note of
  the translation dictionary's filename.
  - on your computer, rename the dict.kobo.zip file to the same name as the
  translation dictionary.
  - rename the original translation dictionary to something else.
  - move or copy the malazan zip file into the device's dictionary directory.
  - unmount the drive, remove the cable.

  now, it should be usable on the device, the big downside is that you'll need
  to select the dictionary to use when you look up a word.  This is slightly
  problematic, as it prevents word lookups in multiple installed dictionaries
  simultaneously.

this is a work in progress, there's still so much work to do, so if you run
across errors or problems, please let me know.

contact me at @asiag0 on telegram or books(AT)idunna.is if you still use email.
