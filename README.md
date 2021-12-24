# TI-Snake
Snake game made for a TI-84 calculator.

Let the program run to completion every time. Ending it early will leave a mess of your window and editor, and waste valuable memory.

This version only works for TI-84 Plus CE, however the code could be adapted to work on older calcualtors. I don't plan to do this because it would probably be too slow.

Use TI Connect to download the files onto your TI-84.

Str0 and list SHI store highscore data. Don't download these if you want a clean leaderboard, but you'll have to input initals after the first few games to fill up the leaderboard.

When you get a highscore, use arrow keys to input initials. Clicking enter will submit. 

If you don't get a highscore, click + to view leaderboards, and enter to close the program. 

Str0 is used to store leaderboard names, so in order for leaderboards to work don't overwrite Str0. There is no easy way to change the string used to store it, other than chaning all instances of Str0 found in the code.

Version number is found at the top of the code. I don't have set rules for changing it, I just make the number bigger when I make changes. If I feel like the change is big enough I'll change the second number instead of the third.

Some calculators are slower than others, so I recommend adjusting the T value to change how much time to wait per frame. The default is 0.18s, and decreases by 0.002s each time a berry is eaten, and is opmtimized for TI-84 Plus CE Python Edition. The T value can be changed by going into the code and changing the value stored to it in line 47, and the time decrease per frame can be changed by changing line 87 (in version 1.4.1).

todo:

improve initial entry for leaderboards using same method as snake movement

optimize initialization code and cleanup code, remove uneeded characters

remove blank lines in main loop (it will make it slightly faster, so i'll do this later when i'm more confident i'll do less maintanence)
