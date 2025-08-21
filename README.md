# Schematic_to_Mcpack
An all in one tool for turning virtually any schematic file into one of my .mcpack files. 

There are two options for output and usage (if you download the project only one from the website).

Usage - https://originals-schematic-to-mcpac.onrender.com

99% of schematics should be perfectly fine to run through the website version where you can simply upload the schematic and assign a name.  Everything else is handled automatically.  The given name will be the name of the output file and the pack when inside of minecraft so you should make it memmorable.

If you download the project to run on your own you get an extra option.  You will need to install node and activate the files from command line everything else should be included in the download.  To set it up simply put all the downloaded files from the zip into a singular folder.  Then inside of the same folder add your schematic or .schem file.  Now just open command line (make sure your executing in the file path where you put the download at) and run 

node commands.mjs schemname "Pack Name"   for option 1 (see below)

node commands.mjs schemname   for option 2 (see below)

replace schemname with your schematic files exact name - Ex portal.schem

"Pack Name" Requires the qoutes and will act as the pack name

Option 1 - Mcpack

This is the main function of the project where it turns whatever schematic file into a .mcpack.  This pack has a new item in the items tab of the creative inventory called "Build Loader" which is how you load the build.  There is a full help guide in said menu if you cant figure it out give that a read first.  Remember there is no undo button (yet at least) so maybe use a testing world first.

Option 2 - Command Dump

This isnt as practical for most people but in case you want the output to be all of the commands to build the structure in a singular text file this is also available.  All commands are formatted in bedrock edition setblock and fill commands and to my best efforts will take as minimal storage space as possible.  These are the same output commands found in option 1 but they arent split into valid .mcfunctions files.
