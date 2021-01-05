# graphics-source
Heya! ink here. 

This page is an organizational aid for graphics hosting for <a href="https://dragonheaven.herokuapp.com/#">Dragon Heaven's custom client</a>.

If you want your files added, please feel free to contact me - I can be reached on Discord (inkbug#7658) and on <a href="https://www.smogon.com/forums/members/inkbug.522695/">Smogon Forums</a> - or to submit a PR! It's generally easier for me to add files directly using Github Desktop though, so sending me a zip or a place to download all the files is preferable.

Here are some guidelines for contributing to this database:

# 1: File paths
The main folder for the mod in question should be named the same as your mod's modid, i.e. the same name as its folder in DH's mods folder on the server. Inside, you need:
- /front/ 
- /front-shiny/ 
- /back/ 
- /back-shiny/ 

Your sprites go in their respective folders. The filenames are in all lowercase with no spaces, hyphens or special characters - "Mega Meowstic F" may be called meowstic-f-mega in the code, but it needs to be meowsticfmega.png here. 

I have a "sprites" folder in between the mod folder and the folders where the sprites actually go because that makes it easier for me to copy things around to where they need to go. 

# 2: Sprite specifications
The sprites that Showdown uses need to be very specific sizes in order to display proplerly. 

- **Battle sprites - front, back, and shiny - all need to be _96x96 px_**. If they are not, the battle window will squish them to be 96x, and they will display weird and blurry and stretched.
- **Menu icons need to be _40 px wide by 30 px tall_.** If they are larger than this, the battle will crop them to that size. 

# 3: Maintenance 
If old sprites need to be updated, just let me know, or submit a branch! I can update this database very quickly. 

Okay I think that's all for now! I'll update this later if i think of anything else lmao.
