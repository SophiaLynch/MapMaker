# MapMaker

Sophia-edit2 notes:
Changed Map text box to a Domain Up Down since I feel like maybe it could work better, but if you disagree then I understand and it's an easy change. So when you create a new map, it should add in a Map 2 option. Not entirely sure how to go about clearing the previous info though.

Added another possible way to save files. Unsure of which would work better since I can't test it without the array.

sam-11/11 edits :
Took info Prof. Kalb put in and began expanding it to cover all four players' icons, locations, etc.

Sophia-milestone3 edits:
Thought about Prof. Kalb's advice on some of the buttons. Fixed the save button; it now writes to a textfile all of the information. Clear and Create New work better now as well.

Sophia edit 4 notes:
Clear works properly. Added in functionality for "upload background" button. It just shows the file location for whatever image you choose. Still need to figure out how to make a save file dialog work when creating a new map...the way I tried made it crash.
 
Sophia edit 5 notes:
Added in a save file dialog that comes up when the users tries to clear or create new. Prompts them to go back and save before making changes.

Sophia edit 6 notes: 
Uploaded the mostly complete code to Github (both code from me and Sam to prevent there from being a zip file in the Github).

Sam - 12/9 edits : 
Player spawning points are added to the map field properly and move around properly without arbitrarily resetting. Background can now be uploaded and appears in the map field. Began working on the upload button. Has bug of first click in map field will move p1spawn always.


Sam - 12/10 edits :
Resized GUI and Map Field so that size was proportional to 1920x1080 images that Tucker creates for background. Finished upload button (tool uploads saved .txt files). Fixed bug from 12/9 of first click in map field moving p1spawn. 


Sam - 12/10 edits 2 :
Finished adding in code for bosses once art comes in (used placeholder art to make sure everything works properly).

Sam - 12/10 edits 3 :
Added missing code for loading boss info back from saved file, and fixed issues with clear button not clearing map field. Clear button requires a click in the map field area to actually clear display. Also an error in reading in background images because file path is different format than lab computers where work was initially done. Needs fixing. 
NOTE : Sophia updating actual commits to the project for me, since I'm a loser who can't figure out how to do anything but commit zips to master. 
