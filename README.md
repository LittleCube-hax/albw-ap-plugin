# ALBW AP on a 3DS

## CURRENTLY THIS MUST BE RUN ON THE CUSTOM VERSION OF THE APWORLD!! You need to install the included `.pyd`/`.so` file too.

1. Download the `plugin.3gx`, `albw-ap-plugin-support.apworld`, `.pyd` file (or `.so` file on non-windows) and `Luma3DS` files from [releases](https://github.com/LittlestCube/albw-ap-plugin/releases/latest).

2. Copy `plugin.3gx` to `/luma/plugins/00040000000EC300/` on your SD card.

3. Install the apworld file, and copy the `.pyd`/`.so` file to `Archipelago/lib`.

4. Once you generate a zip from the .apalbw patch, copy the folder inside to `/luma/titles/` on your SD card.

5. Re-insert your SD card into your 3DS and power it on.

6. On the Luma3DS configuration screen after power-up (if this screen does not show up, hold SELECT during power-up):
	1. _Make sure_ that `Enable loading external FIRMs and modules` does **NOT** have an x next to it. If so, disable it.
	2. Turn `Enable game patching` on and make sure it **DOES** have an x next to it.
	3. Press Start or choose `Save and exit`.

7. Press L+DPadDown+Select to open the Rosalina menu, and make sure that `Plugin loader` is set to `[Enabled]`.

8. Run A Link Between Worlds.

9. At the end of the red 3DS loading screen, you should see a blue flash. This means the plugin has loaded successfully.

10. Run the command on-screen into your ALBW APWorld client.

11. Profit.