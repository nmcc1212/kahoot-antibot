Kahoot AntiBot
==============

This script uses a "Levenshtein distance" formula, this compares usernames to determine similarity, taken from [Stackoverflow.com](https://stackoverflow.com/questions/10473745/compare-strings-javascript-return-of-likely) DISCLAIMER: this wont work if all the bots have completely different usernames, but most bots just do bot-1, bot-2 etc.

* * *

**

INSTALLATION
============

**

1.  Make sure you have installeda script manager such as https://www.tampermonkey.net/ in your brower [(Chrome Extension)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
2.  Install the script by clicking [here] https://github.com/nmcc1212/kahoot-antibot-for-streamers/raw/main/kahoot-antibot.user.js

4. When the tampermonkey extensions opens, press install, the tab should now close
![TamperMonkey install](https://github.com/nmcc1212/kahoot-antibot-for-streamers/raw/main/docs/Screenshot%202021-01-05%20at%2019.13.42.png)
5. Open a kahoot game. The antibot should be installed if you see some text that says "v2.x.x @theusaf at the bottom right.

6. Have fun with 

* * *

Features
--------

*   Remove all bots with a similarity rating of 60%

*   You can set the similarity in the config. Lower numbers = more strict

*   Extend Kahoot! questions by a few seconds to help with stream delay.
*   Enable Answer Streak Bonus Points!
*   Prevent answers that happen before 0.5 seconds after the question starts
*   Ensure names are generated by Kahoot! when using the friendly nickname option

*   Disclaimer: some non-kahoot generated names may still make their way in

*   Block many naming formats that bots use.
*   Block common bots in team mode
*   Prevent brute forcing the two-step code
*   Auto-lock your game when you get spammed with bots (Enable it in the config). Automatically unlocks after one minute.
*   Auto-start your game when auto-progress is enabled. (Enable it in the config). This will start the quiz if a player joins the lobby after the specified amount of time to prevent a never ending lobby.

How to improve anti-botting:
----------------------------

Sometimes, just an antibot is not enough... Here are ways to prevent bots from joining your games to the best of your ability

1.  **Enable Friendly Names** - This brings out the most power of the antibot, blocking 99% of bots. (until someone realized how to bypass this)
2.  **Enable 2FA** - Many bots try to brute force this. The AntiBot detects this and can block them.
3.  **Enable Team Mode** - While team mode no longer prevents most bots from joining, it can help filter out some bots that use the same patters for teams. Some bots may still not support team mode, so this will help.

* * *

Features planned:
-----------------

*   More Blocking Options (When new botting patterns are found).
*   Prevent answers during team talk
*   Impove performance or edit the way Kahoot's timers work
