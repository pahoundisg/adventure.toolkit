Contributions:
Gianna: rewrote the guard code, the intro scene, the fork scene, and the ending scene
Alanna: added a cave scene, added the play again function, altered the coin and seconds to deal with negative inputs, changed the age function to halt the adventure if eligibility not met

#failure without torch path right
Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 800
H:MM:SS = 0:13:20
Enter copper pieces (cp): 80
Coins → gp:0  sp:8  cp:0
Enter age: 19
Citizen (y/n): y
Eligible? True

=== Mini-Adventure ===
What is your name, adventurer? Alanna
Do you carry a torch? (y/n): n
# DEBUG: name=Alanna, has_torch=False

Welcome, Alanna.
The air grows colder as you cross the threshold of the crumbling castle.
From the shadows, a flock of ravens burst upward, their wings echoing against the empty halls that once hosted royalty.

You reach a fork deep within the crumbling castle.
To the left, broken walls are lined with faint carvings, half-buried in rubble.
To the right, the corridor narrows, its silence broken only by falling stone.
Choose your path (left/right): right
In the dark, falling bricks echo through the castle. You push on, but every wall and door seams identical.

You see a cave. A strange sensation pulls you onward.
Choose (enter/exit): exit
It was too dark. You feel like you dodged a bullet.
You press forward into the dark corridor.
A thunderous crack splits the air — the ceiling gives way, burying the path behind and ahead.
The castle has claimed another soul,stories you were told as a child about the legend of the Sword of Fallen Kings.
Do you want to play again? (y/n): n
Thanks for playing!

#failure without torch path left
Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 200
H:MM:SS = 0:03:20
Enter copper pieces (cp): 200
Coins → gp:0  sp:20  cp:0
Enter age: 19
Citizen (y/n): y
Eligible? True

=== Mini-Adventure ===
What is your name, adventurer? Alanna
Do you carry a torch? (y/n): n
# DEBUG: name=Alanna, has_torch=False

Welcome, Alanna.
The air grows colder as you cross the threshold of the crumbling castle.
From the shadows, a flock of ravens burst upward, their wings echoing against the empty halls that once hosted royalty.

You reach a fork deep within the crumbling castle.
To the left, broken walls are lined with faint carvings, half-buried in rubble.
To the right, the corridor narrows, its silence broken only by falling stone.
Choose your path (left/right): left
Without light, the carvings remain hidden. You stumble through rubble, unsure if you missed a clue.

You see a cave. A strange sensation pulls you onward.
Choose (enter/exit): enter
Your footsteps echo ominously. You sense an ominous presence
You wander blindly among rubble and ruin. The markings are lost to you, and the castle offers no answers.
At last, you stagger back to where you began, empty-handed, and defeated. Perhaps the legendary Sword of Fallen Kings never existed to begin with...
Do you want to play again? (y/n): n
Thanks for playing!

#Success path
Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 300
H:MM:SS = 0:05:00
Enter copper pieces (cp): 300
Coins → gp:0  sp:30  cp:0
Enter age: 18
Citizen (y/n): y
Eligible? True

=== Mini-Adventure ===
What is your name, adventurer? Alanna
Do you carry a torch? (y/n): y
# DEBUG: name=Alanna, has_torch=True

Welcome, Alanna.
The air grows colder as you cross the threshold of the crumbling castle.
From the shadows, a flock of ravens burst upward, their wings echoing against the empty halls that once hosted royalty.

You reach a fork deep within the crumbling castle.
To the left, broken walls are lined with faint carvings, half-buried in rubble.
To the right, the corridor narrows, its silence broken only by falling stone.
Choose your path (left/right): right
You spot a cracked archway ahead, nearly collapsed — beyond it lies a sealed door marked with a sword rune.

You see a cave. A strange sensation pulls you onward.
Choose (enter/exit): exit
You can't help but feel like you missed out on something.
Etch your code guess upon the stone (3 attempts remain): 77
The old stones tremble... the gates creak open. You have succeeded.
With a final effort, the seal breaks open. Within lies the Sword of Fallen Kings, glowing faintly in the dark.
The weapon is yours — a relic, a myth once told as a bedtime story to children across the realm, now bound to your fate.
Do you want to play again? (y/n): n
Thanks for playing!

#Failure path
Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 200
H:MM:SS = 0:03:20
Enter copper pieces (cp): 20
Coins → gp:0  sp:2  cp:0
Enter age: 18
Citizen (y/n): y
Eligible? True

=== Mini-Adventure ===
What is your name, adventurer? Alanna
Do you carry a torch? (y/n): y
# DEBUG: name=Alanna, has_torch=True

Welcome, Alanna.
The air grows colder as you cross the threshold of the crumbling castle.
From the shadows, a flock of ravens burst upward, their wings echoing against the empty halls that once hosted royalty.

You reach a fork deep within the crumbling castle.
To the left, broken walls are lined with faint carvings, half-buried in rubble.
To the right, the corridor narrows, its silence broken only by falling stone.
Choose your path (left/right): left
The torchlight reveals ancient carvings — a map etched in stone, pointing toward the sword’s chamber.

You see a cave. A strange sensation pulls you onward.
Choose (enter/exit): enter
Your torch reveals a glimmering treasure box.
The carvings lead you into a hidden chamber. At first, it feels like discovery...
But as the floor gives way beneath you, you realize too late — the map was a decoy, a trap left by the castle’s last guardians.
You plunge into darkness, the echo of your fall swallowed by the ruins.

#ineligible
Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 3600
H:MM:SS = 1:00:00
Enter copper pieces (cp): 900
Coins → gp:0  sp:90  cp:0
Enter age: 17
Citizen (y/n): y
Eligible? False
You are not eligible to enter the castle.


Adventure Toolkit — Chapters 1–3,5
=== Prep Utilities ===
Enter total seconds: 367
H:MM:SS = 0:06:07
Enter copper pieces (cp): 1349
Coins → gp:1  sp:34  cp:9
Enter age: 17
Citizen (y/n): y
Eligible? False


# adventure.toolkit
adventure toolkit
