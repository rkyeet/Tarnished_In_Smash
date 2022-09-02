# Tarnished_In_Smash
Implementing the Tarnished from Elden Ring into Smash Ultimate

This project is a large-scale, 1-man effort to implement a competitive-viable new character into Smash Ultimate, using models, animations and mechanics from Elden Ring. 

The gimmick is that it will have switchable loadouts, a main and offhand weapon which completely change the moveset and each have a unique passive ability. 
Details can be seen below. 

The Tarnished is medium weight, equipped weapons don't change this. average jump height, low double jump height. Fast fall speed, but low air speed. Average speed on the ground. 

<!-- Yay, no errors, warnings, or alerts! -->


<table>
  <tr>
   <td>trivial
   </td>
   <td>easy
   </td>
   <td>medium
   </td>
   <td>hard
   </td>
   <td>????
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Throws
   </td>
   <td>forward
   </td>
   <td>down
   </td>
   <td>up
   </td>
   <td>back
   </td>
  </tr>
  <tr>
   <td>General bad throw range, no kill throws.
   </td>
   <td>sword critical animation. sideways angle.
   </td>
   <td>Inescapable frenzy. fire effect
   </td>
   <td>great weapon critical animation using sword
   </td>
   <td>backstab. crumple effect
   </td>
  </tr>
  <tr>
   <td>Relatively high damage: forward&lt;up&lt;down&lt;back
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Tilts
   </td>
   <td>forward
   </td>
   <td>down
   </td>
   <td>up
   </td>
   <td>Jab
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>heavy sword swing- classic L1
   </td>
   <td>crouched sword R1 string
   </td>
   <td>overhead swing (heavy dash attack?)
   </td>
   <td>classic sword R1 string
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Slow but a good killmove
   </td>
   <td>fast shield poke/combo tool
   </td>
   <td>anti-air
   </td>
   <td>3 or 4 hit combo
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Dash Attack
   </td>
   <td>Sword light dash attack
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Aerials
   </td>
   <td>forward
   </td>
   <td>down
   </td>
   <td>up
   </td>
   <td>back
   </td>
   <td>neutral
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>sword jumping 1H heavy
   </td>
   <td>plunging attack(2h jump heavy)
   </td>
   <td>raptor of the mists
   </td>
   <td>sword jump 2H light
   </td>
   <td>sword jumping 1H light attack
   </td>
  </tr>
</table>


Main hand changes smash attacks/equipped weapon for tilts, and passive 1. Tilt animations stay the same.


<table>
  <tr>
   <td>main hand/Smash attacks:
   </td>
   <td>side
   </td>
   <td>down
   </td>
   <td>up
   </td>
   <td>weapon
   </td>
   <td>passive
   </td>
   <td>description
   </td>
  </tr>
  <tr>
   <td>1. great club (wretch)
   </td>
   <td>side swipe
   </td>
   <td>big overhead
   </td>
   <td>Stamp (upward cut)
   </td>
   <td>ornamental straight sword
   </td>
   <td>Bloodhound Step
   </td>
   <td>Dodging renders you briefly invisible and is much longer
   </td>
  </tr>
  <tr>
   <td>2. Golden Halberd (tree sentinel)
   </td>
   <td>Halberd stab (heavy dash attack)
   </td>
   <td>Halberd heavy spin slash
   </td>
   <td>Golden Vow (overhead aoe)
   </td>
   <td>Noble's slender sword
   </td>
   <td>High Poise
   </td>
   <td>all attacks have super armor
   </td>
  </tr>
  <tr>
   <td>3. Dark Moon Greatsword (Raging Wolf)
   </td>
   <td>moonlight greatsword
   </td>
   <td>Gravitas
   </td>
   <td>Giant Hunt
   </td>
   <td>SoNaF
   </td>
   <td>Carian Filigreed Crest
   </td>
   <td>lowers FP cost of specials by 25%
   </td>
  </tr>
  <tr>
   <td>4. Academy Glintstone staff (mage)
   </td>
   <td>Meteorite
   </td>
   <td>Rock Blaster
   </td>
   <td>loretta's greatbow
   </td>
   <td>carian slicer sword
   </td>
   <td>Magic Affinity
   </td>
   <td>Deal 25% damage through shields
   </td>
  </tr>
  <tr>
   <td>5. Erdtree seal (prophet)
   </td>
   <td>Rings of Light
   </td>
   <td>Law of Regression
   </td>
   <td>Elden Stars
   </td>
   <td>coded sword
   </td>
   <td>Erdtree's Protection
   </td>
   <td>take 15% less damage and knockback
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Wretch
   </td>
   <td>VERY slow, huge power, can make up for speed with the fast dodge.
   </td>
  </tr>
  <tr>
   <td>Sentinel
   </td>
   <td>slow but long reaching attacks. Applies armor to offset speed
   </td>
  </tr>
  <tr>
   <td>Raging Wolf
   </td>
   <td>fast, with interesting qualities. Moonlight greatsword is a projectile smash, Gravitas pulls inwards. Giant Hunt has a diagonal hitbox.
   </td>
  </tr>
  <tr>
   <td>Mage
   </td>
   <td>fast and long range smashes, relatively low knockback.
   </td>
  </tr>
  <tr>
   <td>Prophet
   </td>
   <td>medium speed, medium damage, medium range. The beginners choice.
   </td>
  </tr>
  <tr>
   <td>Smart (staff)
   </td>
   <td>emphasis on devastating specials
   </td>
  </tr>
  <tr>
   <td>Strong (Shield)
   </td>
   <td>Balanced. good projectile, recovery and self-heal
   </td>
  </tr>
  <tr>
   <td>Faithful (seal)
   </td>
   <td>self-buff, with invincibility and lingering hitboxes on attacks
   </td>
  </tr>
  <tr>
   <td>Dextrous (dagger)
   </td>
   <td>highly mobile, high damage, low verticality
   </td>
  </tr>
  <tr>
   <td>Toxic (katana)
   </td>
   <td>complex and difficult moves, but insane damage if pulled off
   </td>
  </tr>
</table>


Offhand changes Specials and Passive 2


<table>
  <tr>
   <td>offhand/Specials:
   </td>
   <td>side
   </td>
   <td>down
   </td>
   <td>up
   </td>
   <td>neutral
   </td>
   <td>extra effect
   </td>
   <td>passive
   </td>
   <td>description
   </td>
  </tr>
  <tr>
   <td>1. Smart: Lusat's Glintstone staff
   </td>
   <td>comet azur
   </td>
   <td>terra magica
   </td>
   <td>Rennala's full moon
   </td>
   <td>Flask Drink (regain FP for specials)
   </td>
   <td>For 10 seconds specials dont cost FP
   </td>
   <td>Cerulean Dagger
   </td>
   <td>Successful grabs (5%), smash attacks (2%) and kills (10%) restore FP
   </td>
  </tr>
  <tr>
   <td>2. Strong: Fingerprint Shield
   </td>
   <td>throwing knife
   </td>
   <td>guard counter
   </td>
   <td>ground slam
   </td>
   <td>Flask Drink (regain FP for specials)
   </td>
   <td>Increase damage taken and dealt for 10s
   </td>
   <td>Blessed Dew Talisman
   </td>
   <td>Regain 0.5% per second
   </td>
  </tr>
  <tr>
   <td>3. Faithful: Giant seal
   </td>
   <td>Crucible horns
   </td>
   <td>Flame Grant me Strength
   </td>
   <td>Ancient Dragon Lightning Spear
   </td>
   <td>Flask Drink (regain FP for specials)
   </td>
   <td>Invincible for 1 hit
   </td>
   <td>Radagon Icon
   </td>
   <td>Smash attacks charge 20% faster
   </td>
  </tr>
  <tr>
   <td>4. Dextrous: Black knife dagger
   </td>
   <td>bloodhound's finesse
   </td>
   <td>parry
   </td>
   <td>blade of death
   </td>
   <td>Flask Drink (regain FP for specials)
   </td>
   <td>Gain bunny ears
   </td>
   <td>Powerstance
   </td>
   <td>Deal 15% more damage
   </td>
  </tr>
  <tr>
   <td>5. Toxic: katana (Rivers of blood)
   </td>
   <td>Corpse Piler 1st part
   </td>
   <td>seppuku
   </td>
   <td>Waterfowl Dance
   </td>
   <td>Flask Drink (regain FP for specials)
   </td>
   <td>For 10 seconds become metal
   </td>
   <td>Bleed Affinity
   </td>
   <td>build a meter, when it fills, the enemy takes 40% damage.
   </td>
  </tr>
</table>


Flask Drink: Regain 75% of your FP + extra effect based on offhand. Start with charges = to number of stocks (stock), or multiples of 2min (time). Gain 1 charge on a KO


<table>
  <tr>
   <td>Weapon
   </td>
   <td>Move
   </td>
   <td>Cost
   </td>
   <td>Description
   </td>
  </tr>
  <tr>
   <td>Staff
   </td>
   <td>Comet Azur
   </td>
   <td>high -> low (constant drain)
   </td>
   <td>large horizontal beam attack. This attack lasts for as long as you hold the button.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Terra Magica
   </td>
   <td>high
   </td>
   <td>create a platform that boosts damage by 25% for anyone on it. Lasts a very short time if cast in the air, longer if cast on the ground.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Rennala's full moon
   </td>
   <td>high
   </td>
   <td>float into the air and create a large, homing moon that freezes enemies. Does not cause special fall.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Shield
   </td>
   <td>Throwing knife
   </td>
   <td>low
   </td>
   <td>throw a small, fast, low damage knife forwards.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>guard counter
   </td>
   <td>low
   </td>
   <td>hold to enter stance. When attacked from the front, launch a devastating counter with high knockback. Can move while in the stance, but cannot perform attacks or jump
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Ground slam
   </td>
   <td>mid -> high
   </td>
   <td>launch youself high in the air, then slam down with great force. Holding the button charges the attack, turning it into Golden Slam, with a higher jump and aoe explosion
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Seal
   </td>
   <td>Crucible Horns
   </td>
   <td>mid -> high
   </td>
   <td>Sprout horns from your shoulder and dash forwards. Charge for invincibility from the front and longer distance
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Flame Give Me Strength
   </td>
   <td>mid
   </td>
   <td>increase own damage by 25% for 30 seconds.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Ancient Dragon Lightning Spear
   </td>
   <td>mid -> high
   </td>
   <td>rise into the air wreathed in lightning, then throw a lightning spear in to the ground in front of you. hold to rise further and throw a second spear
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Dagger
   </td>
   <td>Bloodhounds finesse
   </td>
   <td>low -> mid
   </td>
   <td>jump backwards with a swipe of your weapon. Press again to follow up with a large, invisible forwards leap followed by an attack
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>parry
   </td>
   <td>low
   </td>
   <td>interrupt an enemy attack to briefly stun them, then riposte, dealing huge damage. Can be activated on shield-broken, buried, or sleeping enemies. (hopefully)
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>blade of death
   </td>
   <td>mid
   </td>
   <td>rise into the air and fire a dark flame at the enemy. (fast, lock-on projectile that deals DoT)
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Katana
   </td>
   <td>Corpse Piler
   </td>
   <td>mid
   </td>
   <td>a flurry of bloody slashes in front of the user. Deals some self-damage, but builds a lot of bleed on the opponenet. Damage is higher on the sword than the blood strikes.
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>seppuku
   </td>
   <td>low
   </td>
   <td>imbue bleed buildup on tilt attacks and aerials, with a small aoe knockback. Deal some self damage
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Waterfowl Dance
   </td>
   <td>low -> mid -> high
   </td>
   <td>press to rise into the air, then launch in an input direction at high speeds, swinging with fast strikes. Press again to enter the second part of the combo, moving in another direction with more strikes. Press a third time to dash towards the closest enemy, swinging and activating an area of delayed sword bursts.
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Final Smash
   </td>
  </tr>
  <tr>
   <td>Summon Hoarah Loux on activation, who runs past the Tarnished as they dodge-roll.
<p>
Enemies caught by him enter a cutscene where he powerbombs them into the path of Malenia, who executes a combo, then stops and looks up to observe the Radahn Meteor falling into them, ending in an explosion
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Taunts
   </td>
   <td>right
   </td>
   <td>left
   </td>
   <td>down
   </td>
   <td>up
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>wave "Hey!"
   </td>
   <td>dejection
   </td>
   <td>point down
   </td>
   <td>Golden Order Totality
   </td>
  </tr>
</table>


Victory screen based on main hand weapon


<table>
  <tr>
   <td>Wretch
   </td>
   <td>Patches Squat
   </td>
  </tr>
  <tr>
   <td>Sentinel
   </td>
   <td>Bow
   </td>
  </tr>
  <tr>
   <td>raging wolf
   </td>
   <td>Strength
   </td>
  </tr>
  <tr>
   <td>Mage
   </td>
   <td>Erudition
   </td>
  </tr>
  <tr>
   <td>Sage
   </td>
   <td>Rapture
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>Skins
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Default
   </td>
   <td>Red Phantom
   </td>
   <td>Gold phantom
   </td>
   <td>Blue phantom
   </td>
  </tr>
</table>

