![a](https://raw.githubusercontent.com/denizonm/Collections-for-GarlicOS/main/CFW/skin/system/COLLECTIONS.png)
# Collections for GarlicOS! 
now you can obsessively make cool little game collections! Huzzah!

# Installation
1. copy folders to the root of the SD card
2. open up /CFW/config/coremapping.json
3. insert this to a new line after the curly bracket (the one before the FBA line)in said file:
    "COLLECTIONS": "/bin/sh",
4. (optional) backup the /CFW/retroarch/.retroarch/content_favorites.lpl file in case i made a mistake
You're done!

# Usage
pressing a collection will autosave the current one and replace the favorites with the selected one
(your current favs will autosave to the "Favorites" collection when you first use it.)

# Adding New Collections
1. copy & paste any collection file (don't touch the "Coll" folder)
2. Rename copy to the desired collection name
That's it!

# Tips
- the play history is great for transferring games between collections
- you can empty collections or undo the last save with their respective scripts
- all the actual collection data is in the "Coll" folder. Back it up whenever you can.
