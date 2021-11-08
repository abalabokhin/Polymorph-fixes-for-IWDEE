# Polymorph (and other) fixes for IWD:EE
Download: https://github.com/D2-mods/Polymorph-fixes-for-IWDEE/releases  
Game version: IWD:EE v2.5 and v2.6, and possibly older versions (untested)


#### WHAT THIS MOD DOES:

Fixes stats of some polymorphs and edits descriptions of Shapechange forms to all share the same layout. The descriptions for fire/earth elemental now also list the correct resistances (identical to Druid forms). Also makes minor changes to the Mind Flayer's Psionic Blast.

UPDATE v1.3: added a fix for nymph.BCS (Call Woodland Beings) crashing with EEex (v0.8.7-alpha)


#### INSTALL INFO:

Extract to game folder and run the setup to install or uninstall. I'm not familiar with Mac/Linux, but installing should be the same as other mods (mod packages are cross-platform). By its nature, this mod will conflict with any mod that makes changes to stats of Shapechange forms.


#### FIXES/TWEAKS:

Polymorph Self
- Winter Wolf, Boring Beetle, and Polar Bear are no longer permanently hasted

Shapechange (all changed to match descriptions)
- Giant Troll Strength changed from 18 to 18/00
- Water Elemental weapon damage changed from 1d8 to 4d8

Text edits:
- all Shapechange forms (consistent layouts and accurate stats)

Psionic Blast
- added missing description for v2.5
- uses IWDEE v2.6 version as a base, with a few changes:
1. stun duration changed to 5 rounds (from 10) to match description
2. ability regenerates when used (this just skips the extra step of needing to re-shapechange into a Mind Flayer if you wanted to use Psionic Blast more than once)
3. added back the orb thing over a stunned creature

Call Woodland Beings
- patches the nymph's AI script to fix a crash with EEex (v0.8.7-alpha)
