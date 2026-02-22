# Snafu-Expansion-Mod-Market-Files
Files needed for Trader &amp; Market to sell SNAFU weapons in Expansion Market

The Trader files have SNAFU product as well as Expansion categories available. If you only want them to sell SNAFU just remove any item in the categories that does not have SNAFU_ in front of it. I suggest keeping it as is though.
If you do edit these - before you upload to your server RUN YOUR FILE THROUGH A JSON CHECKER when you are done editing. https://jsonformatter.org/

These are priced via Grok using real world criteria plus a premium for the Post Apocalyptic scenario DayZ presents. Everything for the most part takes into account what other similar things cost.
The reasoning behind this is to avoid having a ridiculous server economy where things cost tens of thousands of dollars or hundreds of thousands, lol. I try to avoid the temptation to create "rarity" by pricing.
Having every SNAFU rifle cost 25,000 is absurd, lol. You can easily go into your types.xml file and change value to Tier 4, so it only spawns in high risk areas. In some instances you may want to
remove the weapon from the market entirely and change the types.xml Nominal value to 1 so only 1 pops on map. Or change the value to 0 so none ever spawn and you can offer one as a reward for a big event or equip a tough AI with one to loot. 
Or sell the weapon, but not the ammo, so players have to go to risky places to scrounge for ammo for their Barrett 50cal head exploder...

But, if your server economy is fucked & players are minting cash by mining gems or growing weed, feel free to change all the prices to 100,000 per rifle ;) Don't contact me to debate prices. 
Just change them if you don't like them, lol...




I have included the types & spawnable types files as well as an example cfgeconomycore.xml file for your missions folder set to use those folder/file names so you can add them to your server.
Other people have worked on these before me, but I have gone through and corrected type names and other errors that were causing things not to spawn or be unavailable at the Trader. 
As always, before uploading these to your server, check them with an XML validator first: https://jsonformatter.org/xml-validator

All you should need with these is the mod itself correctly installed. https://steamcommunity.com/sharedfiles/filedetails/?id=2443122116&searchtext=snafu
