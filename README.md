![a](https://raw.githubusercontent.com/denizonm/Collections-for-GarlicOS/main/CFW/skin/system/COLLECTIONS.png)
# Collections for GarlicOS! 
now you can obsessively make cool little game collections! Huzzah!

## What is it?
Basically, it creates a new "system" that has a bunch of names of "Collection"s.
Pressing the collection replaces the current favorites with the contents of the selected collection.
(at first they will be empty, you can fill them up by favoriting new games)
Selecting a new one also autosaves the currently active one (you can undo this if you did it by accident)

So, let's say you want to make a collection for games you have beaten.
You would:
- tap the "Beaten" collection from the new Collections system icon
>this would empty the favs you have rn, since you havent put anything into the "Beaten" collection yet. (don't worry, your current favorites were saved into the "Favorites" collection.)
- favorite the games you have beaten, this puts them in the collection.
- now you can switch the collection, let's say you want your old favs back, then press the "Favorites" collection and now they are back.
- as you can guess, pressing "Beaten" will bring back the ones you chose during this tutorial.

### Allow this extremely crunchy gif to explain!
![crn](https://github.com/denizonm/Collections-for-GarlicOS/blob/main/ezgif-3-7c09519935.gif?raw=true)

# Installation
1. copy folders to the root of the SD card
2. open up /CFW/config/coremapping.json
3. insert this to a new line after the curly bracket (the one before the FBA line)in said file:
    "COLLECTIONS": "/bin/sh",
4. (optional) backup the /CFW/retroarch/.retroarch/content_favorites.lpl file in case i made a mistake
You're done!

# Adding New Collections and Renaming
>It comes with a bunch of common names for collections like "Beaten" and "To Play". You can rename them to make yours.
## As for adding new ones:
1. copy & paste any collection file (don't touch the "Coll" folder)
2. Rename copy to the desired collection name
That's it!

# Tips
- the play history is great for transferring games between collections
- you can empty collections or undo the last save with their respective scripts
- all the actual collection data is in the "Coll" folder. Back it up whenever you can.
