# malazan-dictionary
quick reference dictionary in stardict and kobo formats.

this is a dictionary project for the Malazan series of books.  the intent of this project is a quick reference usable on the Kobo ereaders, and as stardict format for use with most other digital dictionary programs.

there may be some spoilers, this is unavoidable.  most major spoilers have been removed from the definitions.

the source material was the wiki at http://malazan.fandom.com/, some personal notes, and other input.  suggestions and criticisms are always welcome.

special thanks to reddit user u/sebtree for identifying that the custom-dict directory now works with the current kobo firmware (it didn't used to), simplifying usage.

files:
   - dict.xdxf (xdxf format) - this is the master file, easiest to edit as it's
     basically xml, and very versatile (some other features of the standard I plan to
     exploit in the future)
   - 'kobo' directory: contains the dict.kobo.zip file, which is compatable with the Kobo eReaders. (this will get a more appropriate filename in the next revision)
   - 'stardict' directory: contains the files needed for use with stardict programs.  works perfectly with QDict (on F-Droid).

installation on kobo devices (updated 2023-05):
   to get it to work on a kobo, you'll need a kobo device, and a host computer and usb cable to connect the kobo to it.
   
   1. Connect the kobo to your computer via usb, open your file manager, and navigate to the correct directory.  on linux, from the root level of the device, it would be .kobo/custom-dict/.
   2. Copy over the new dict.kobo.zip file to this directory, (and rename it to 'dicthtml-malazan.zip', if i haven't updated the filename here).
   3. sync and unmount the device.

to use the dictionary on a kobo, use it like the default lookup dictionary - highlight a word and it'll pop up the word definition pane.  Tap the dropdown menu, and select 'dicthtml-malazan', and the definition should appear.  Sadly, kobo devices cannot display definitions from multiple dictionaries simultaneously, you must choose between dictionaries with the dropdown.

this is a work in progress, there's still so much work to do, so if you run
across errors or problems, please let me know.

contact me at @asiag0 on telegram or books(AT)idunna.is if you still use email.
