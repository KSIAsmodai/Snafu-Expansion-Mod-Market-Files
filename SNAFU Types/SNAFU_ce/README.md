Everything that IS NOT A GUN is set to spawn 1 on the map per loot cyle.
flags count_in_hoarder="0" count_in_player="0" count_in_map="1" count_in_cargo="0" crafted="0" deloot="0"

Everything that IS a GUN is set to have only 1 ever until you do a wipe. eg. If someone stuffs one in a barrel, there won't be another spawned.
flags count_in_hoarder="1" count_in_player="1" count_in_map="1" count_in_cargo="1" crafted="0" deloot="0"
 
Everything that is not a machine gun or a sniper rifle has a Police usage, because the police tend to use Military equipment.
usage name="Police"
 
All items have been set to spawn ONLY in Tier 3 & 4 areas of the map
value name="Tier4"
value name="Tier3"
