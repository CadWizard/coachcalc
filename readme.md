# CoachCalc

A grassroots youth football match-day tracker and tactical whiteboard designed to ensure fair playing time and seamless touchline management.


Roadmap

App changes

1) ~~When clock goes past half time and the game is still in the first half then the clock should turn red. Again when the game clock hits full time and the game is in the 2nd half then the clock should turn red - Complete~~

2) ~~Add an new option to reset game - Complete~~

3) ~~Better football design - Complete~~

4) ~~Rename "Official Match Summary Ledger Report" to "Match Summary" and instead of "Home Team Roster Stats" and "Away Team Roster Stats" please use the actual team names - Complete~~

5) Ability to save previous game summary's in the app itself and it does not get wiped when clicking "Reset Squads", however we should be able to select and delete individual ones when needed.


6) ~~Ability to add Red/Yellow cards, these should actually show on the Match Summary.~~


7) ~~Check name change to CoachCalc has been applied~~

8) ~~Scale pitch:~~

~~I want to make sure the pitch scale is correct, these standard sizes exist for a pitch.~~

~~* Pitch Dimensions - 105 metres x 68 metres~~
~~* 6-yard box measures 5.49 metres x 18.29 metres~~
~~* Penalty Spot is 11 metres from the centre of the goal line~~
~~* 18-yard box measures 16.46 metres x 40.23 metres~~
~~* The "D" (penalty arc) on an 18-yard box has a radius of 9.1 metres drawn from the centre of the penalty, however only the portion outside of the 18 yard box is shown.~~

~~I am happy with the current length of the pitch so if we say that is 105 metres and then scale the rest off of that.~~

9) Add a button to copy the match report ready for sharing

10) ~~Half-time and full-time whistles~~, or even a 2 minute warning

11) Add a new and better background

12) ~~Use symbols for the things like play/pause~~
13) ~~Maybe hide the equal play timing behind a drop down~~
14) ~~Maybe hide the Run line/Pass line/clear lines behind a drop down menu (They are not really used during a game but only to give a guide on training routines~~
15) ~~Do I really need an option to change the appearance of the grass (Could hide in a settings menu)~~
16) ~~Add +30 seconds catch-up button to timer controls~~
17) ~~Enlarge player counters by 10% for easier touch targets~~
18) ~~Add collapsible dropdown for the Substitutes Bench~~
19) ~~Move player actions (Goals/Assists/Cards) behind a tap-to-expand player drawer~~
20) ~~Restrict Goals & Assists to on-pitch players only~~
21) Implement local match report file export
22) Add background stadium image and UI opacity slider
23) Add custom kit & shirt designer
24) ~~Tactics Menu Label & Persistence Fix~~
25) ~~Bring on sub in place of player who has last been subbed~~



Notes:

Also ask about creating a beta Android demo and how easy that would be as most coaches won't have a laptop on the sidelines. We need to also look at how we change the view to better suit an iPad or phone.

Possibly look at integration with Comet to pull through player names etc...

------------------------------------------------


What to do when there is another update in code?

Step 1: Open Git Bash in Your Project Folder
Open Git Bash from your Windows Start menu.

Make sure you are inside your project folder. (If you just opened it, you can quickly verify by typing cd /c/Users/YourName/Documents/CoachCalc or whatever your exact folder path is).

---------------------------------------------------

Step 2: Run the Three Push Commands
Type (or copy/paste) these three commands one at a time and press Enter after each:

git add .

What happens: This tells Git to look at your project folder and stage all modified or new files (like your updated tactical_board.html file) so they are ready to be saved.

2. git commit -m "Added a short note about what changed"

What happens: This packages your changes together into a permanent snapshot in your local history. Replacing the text inside the quotation marks with a brief description of what you updated (e.g., "Added New Game reset button") helps you remember what you did in that version.

3. git push

What happens: This uploads your local snapshot up to your secure repository on GitHub using the Personal Access Token you saved earlier.

Summary Checklist for Every Update
Whenever we make progress together and you save your file:

Bash
git add .
git commit -m "Describe your update here"
git push



And that's it! Your code is safely synced to the cloud. Whenever your usage limit resets, just let me know what you'd like to work on next for CoachCalc!

Test line