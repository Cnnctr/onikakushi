PS3 Voice Only Patch
-----------------------------------------------------------------------------------------
For Higurashi No Naku Koro Ni - Chapter 1 Onikakushi, Steam Version

This is a modified version of the combined patch for those who wish to play only with the added voices and without altered graphics.
Combined patch can be found here: https://github.com/higurashi-mod/onikakushi

Download and installation:
-----------------------------------------------------------------------------------------
Download the master file here: https://github.com/Cnnctr/onikakushi/archive/master.zip

There are two versions. No_stops will continue playing voice even after you click out the line. Stops will cut the voice.
Decide on your preferred version, open it, you see two folders. Install both folders into StreamingAssets folder.
If prompted to overwrite current files, overwrite them.
You backed up your files, right?

Grab HigurashiPS3-Voices01.zip: https://mega.co.nz/#F!SRt1DTKI!0vSWMtBLaa2VO0bDgfzb7A

Place s01, s19, s20 folders into streamingassets/SE folder

Troubleshooting:
-----------------------------------------------------------------------------------------
> "There's a missing voice in this scene! There's a wrong voice playing!"

Check the Known Issues section of this readme.
If it's not in there, report it. 

> "Why aren't the voices playing?"

If you have 1.00 version of the game, you need to move files from Update folder to Scripts folder. This version didn't support Update folder yet.
Make sure the FULL voice pack is installed.
Make sure your directory is as follows:

<b> ..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\SE\ </b>
   - The SE folder should have s01, s19, and s20 folders from the FULL voice pack

<b> ..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\Update </b>
   - The Update folder should have script files in it such as onik_000.txt, at least 39 onik files, tips files, and an omake txt file

> "It's still not playing."

- Go to <b>..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\StreamingAssets\CompiledScripts </b> 
- Make a copy of the <b>Complied Scripts</b> folder.
- Delete <b>onik_000.mg -> onik_15_03.mg</b> and <b>onik_op.mg</b>
- This will force the game to read the new files.
- If this stops the game from working properly, go to <b>..SteamApps\common\Higurashi When They Cry\HigurashiEp01_Data\ </b> and open <b>output_log.txt</b>, this will tell you which script txt file has the syntax error.

Script Changes:
-----------------------------------------------------------------------------------------
- Day 1:
  - That first scene between Keiichi and Mion was rewritten to match the console version because there were no voices for it.

Known Issues:
-----------------------------------------------------------------------------------------
- Generic:
  - Sometimes the lines don't last long enough for a voice file to play fully. 
    - This is most evident when auto is left on.
  - Sound volume mutes sounds and voices.
    - Unavoidable, since the voices aren't their own thing.

- Tips: 
  - Missing voices for Keiichi's Mom in Tip 20 (At the Seventh Mart)
  - Missing voices for lines 1472 to 1524 in Omake_1 (All-cast wrap up scene)

Credits:
-----------------------------------------------------------------------------------------
- Anon - For providing the PS3 voices and patch.
