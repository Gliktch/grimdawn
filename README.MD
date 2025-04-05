 Grim Dawn Muted Sounds v1.1
=============================

Download here: https://github.com/Gliktch/grimdawn/releases/download/mutedsounds/GrimDawn_MutedSounds_v1.1.zip

### What It Is ###

I find some game sounds (like the crackling of the riftgate, or a couple of the
pet sounds) diminish my enjoyment of the game - and I know I'm not the only one
who feels this way.  Fortunately, there's hope! :)

Files in a particular Grim Dawn folder will override the corresponding files in
the base game, and any mods. This can be used to replace or mute unwanted sound
effects - and I've created some 0-byte empty files with the right filenames and
paths to make this easy for you. This is non-destructive and completely revers-
ible, simply delete these blank files to undo your changes. This works with all
mods or no mods at all, and will not cause any other changes, nor affect things
like Steam achievements.  Hope it helps!

If you have any requests/suggestions of additional sounds worth including, drop
by at the Reddit thread and let us know so it can be added for everyone:

https://reddit.com/r/Grimdawn/comments/1jrajit/muting_unwanted_sounds_without_editing_databases/

  - Aazimox @ Reddit


### How To Use ###

* Open this folder: Documents/My Games/Grim Dawn/Settings
* If you see text files "keybindings" and "options", you're in the right place!
* Unzip the archives here for the replacements you want to make
* If the only folders created are called "sound" or "sounds", then you're good!
* If you end up with folders called anything else, move the "sound" or "sounds"
  folders out of there, until they're living happily alongside your options.txt
* Start the game your normal way - and enjoy your game without annoying sounds!


### That Skill Is Not Ready text ###

If you want to remove the red text which shows every time you try to use skills
when they're on cooldown, you'll have to either extract & edit your own tags_ui
file, removing everything on the line after "tagSkillNotReady={^r}", or you can
use the file I've included.. BUT this file may eventually get outdated, & it'll
only work for English.

* Extract GrimDawn_RemoveSkillNotReadyText.zip into the Settings folder - it'll
  create a text_en folder, with the tags_ui.txt inside that, where I've already
  made the changes for you.  No more nagging about spamming your skills! ;)


### Muted Sounds List ###

___[ GrimDawn_MutedCommonSounds.zip ]___

* Wing Flaps (for Occultist Familiar)

  - sound/enemies/footsteps/wingflap01.wav
  - sound/enemies/footsteps/wingflap02.wav
  - sound/enemies/footsteps/wingflap03.wav
  - sound/enemies/footsteps/wingflap04.wav

* Wind Devil Loop

  - sound/enemies/vocalizations/winddevil/winddevil_ambient_loop.wav

* Bugswarm Enemy Sound

  - sound/enemies/ambient/alivesound_insectbuzz01.wav

* Blade Spirit Loops

  - sound/skillsounds/class04/blade_spirit_loop.wav
  - sound/skillsounds/class04/blade_spirit_loop02.wav

* Ambient - Flies Buzzing

  - sound/environmental/natural/flies_buzz_01.wav

* Ambient - Riftgate Crackling

  - sound/environmental/supernatural/riftgate_loop.wav

* Ambient - Eldritch Rift Crackling

  - sound/environmental/eldritch_rift_loop.wav


___[ GrimDawn_MuteSkillNotReady.zip ]___

* "That skill's not ready" and "I can't do that yet"

  - sound/human/vocals/pcfemale_cooldown01.wav
  - sound/human/vocals/pcfemale_cooldown02.wav
  - sound/human/vocals/pcfemale_cooldown03.wav
  - sound/human/vocals/pcfemale_cooldown04.wav
  - sound/human/vocals/pcmale_cooldown01.wav
  - sound/human/vocals/pcmale_cooldown02.wav
  - sound/human/vocals/pcmale_cooldown03.wav
  - sound/human/vocals/pcmale_cooldown04.wav


___[ GrimDawn_MuteKodama.zip ]___

* That insufferable bloody sound of the Kodama pet casting Regrowth every 2secs
  (this is the main reason I went looking for this solution!)
  This is only relevant for users of the DOM mod or masteries mods with Nature.

  - sounds/spells/nature/regrowthcast.wav

NOTE: This one uses the SOUNDS folder, not SOUND like all the others.
