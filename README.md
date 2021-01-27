# Wynncraft Noteblock OST
Note-by-note Wynncraft music in NBS and MIDI formats.  
Written by the talented people at Wynncraft, more specifically see here: https://wynncraft.gamepedia.com/Music .  
Lincense copied from XavierEXE's playlist: https://www.youtube.com/playlist?list=PLyqkjDCr8kbI3CjNZimiri8shU1GbfJ6E . You should listen to that too if you aren't interested in different instruments / MIDI.  
My piano tutorial playlist using these: https://www.youtube.com/playlist?list=PLDa4Vj43E2e-mCukFLGM5xTLILNZ_daaI .  
For the GitHub repo with the mp3 files look here: https://github.com/Wynntils/WynncraftOST .  
For Scores and MIDI files not included here see Xeoran's work: https://musescore.com/user/7400466/sets/5090208 .

The source csv files found in `cut_csv` were recorded with https://github.com/4321ba/noteblock_music_yoinker and antilagged, so there is no lag. Sadly, there's a bug https://forums.wynncraft.com/threads/music-note-volume-is-messed-up.281761/ that the NBS player plays the wrong volume sometimes, so this is reflected here as well. You can find some pieces that consist of more than one part, you can find the source in `loopable_csv` for them. For NBS and MIDI they are merged together.

NBS files are in the `nbs` folder. I may make them later so they're not just organized by instrument, but by note volume as well. Please do NOT copy these to play on your Minecraft server without the Wynncraft team's approval. (I think it's fine if you play it to your friend e.g. just don't compete with Wynncraft.)

In the `musescore_midi` folder you can find the MIDI files that are best opened in MuseScore to create a score / sheet music from them. This is achieved by making the notes really short (2/20 sec or 3/20 sec) so they don't overlap with each other. MuseScore can then lengthen it if it is needed.

In the `general_midi` folder you can find the MIDI files that can best be played back with a General MIDI compatible soundfont / player. This is the one you can listen to the best if you want to. Here the notes are 1/4 second long.

In the `melodic_percussion_midi` folder you can find the MIDI files that are best suited to be played back with `wynncraft_soundfont.sf2`. The notes are pretty long here and the percussion is not GM MIDI compatible, but preserves pitch. You can use this best if you want to create a custom soundfont to play them back with melodic percussion.

