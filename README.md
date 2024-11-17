**These standalone mods function independently and don't require the original mods.**  

**Installation Instructions:**

1. **Download:** Download the desired mod files.  Ensure you download the `AGOT.zip` file mentioned in the instructions, which contains the load order information for Irony Mod Manager.

2. **Extract:** Extract the contents of each downloaded mod file.

3. **Mod Folder:** Locate your Crusader Kings III mod folder.  This is typically found within your Documents folder, under Paradox Interactive\Crusader Kings III\mod.

4. **Place Mod Files:** Copy the extracted mod folders into the Crusader Kings III mod directory.

5. **Load Order (Irony Mod Manager):** Use the provided `AGOT.zip` file with Irony Mod Manager. This will automatically configure the correct load order for the mods listed in the linked Reddit post [here](https://www.reddit.com/r/CK3AGOT/comments/1gr0jyy/mods_just_sharing_my_essentials_mods_compatible/). This simplifies the process and ensures compatibility.

**Important Notes:**

* **AGOT Micro Mod (Optional):**  The AGOT Micro mod is *optional* but recommended for players experiencing performance issues, especially in the later stages of the game.  It helps optimize the game and reduce lag.

* **Manual Setup for Population Control:** The "Population Control (Reduce late-game lag)" mod requires a manual adjustment for compatibility with AGOT's dragons.  Follow these steps:
  1. Open the "Population Control" mod folder.
  2. Locate the mod's configuration file (likely a text file or a script file).
  3. Find the variable named `AGOT_Dragons_safe`.
  4. Change the value of `AGOT_Dragons_safe` from `0` to `1`.  This will prevent the mod from accidentally culling dragon riders, dragonslayers, and dragons themselves.  This manual change is *essential* for proper functionality with AGOT.  Failing to do so may result in unintended consequences, such as the removal of dragons from the game.
