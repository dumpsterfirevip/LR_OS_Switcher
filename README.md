# LR_OS_Switcher
This tool (bunch of sql statements currently) lets you switch Operating Systems when you are using Lightroom and retain all your photos in a place you expect them. (external drive)


**Converting from Mac to Windows file system for Adobe Lightroom.**

So Lightroom is a pretty nifty tool but when you want to switch operating systems it falls a bit short. 

Officially I think it says you need to export collections from one OS then reimport them in another OS or something like that but.... 

**There's a much much easier way to do switch OS's.**

By making a few database entry changes you can point the Mac OSX folder location to a windows one and avoid a bunch of work, error and time. 

So underneath lightroom is a database and that database is SQLite which makes sense since lightroom is multi-operating system and so is SQLite. SQLite is a self contained database in a single file.

Read the How_to text for detailed instructions.
