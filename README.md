# bahaar-guide  
Guide for Bahaar's Sanctum  

# changes  
- Reduced notice load, mostly by removing front attacks for tank and those which can easily be recognized by flower pattern on ground and his animation, you can uncomment those skills if you want in `skillsList.js` (that file is not auto-updated automatically)
- fixed "use [Stun]" and back attacks warnings not working if you resurrected after dungeon wipe without reentering the dungeon
- more time before actual back attack and the notice for it (a least 0.5sec now) (could be 0.2sec or lower before)
- added message for "use [Regress]" when it's time
- laser items dissapear twice faster to not clutter the battlefield area
- for 270 attack both item lines now dissapear at the same time

# Shinra  
You can make shinra tell you when laser debuff gets added onto you by adding this event into it https://github.com/neowutran/ShinraMeter/pull/455/files  