# Chunky Plugins

---

The functionality of Chunky can be extended with plugins. Plugins can add new blocks, new post-processors, and even new renderer implementations.

[:material-puzzle: Get plugins](../plugin_list){ .md-button }

---

## Installation

Plugins are usually distributed as JAR files. To install a plugin, follow the instructions below.

- Step 1: Download the plugin JAR file.

- Step 2: Move the plugin to the "plugins" directory of the Chunky [settings directory](../../getting_started/configuring_chunky_launcher#advanced-settings). If you do not know where it is located, then skip this step.

- Step 3: Start the Chunky Launcher.

- Step 4: Click the [`Manage plugins`](../../getting_started/configuring_chunky_launcher#advanced-settings) button to open the [`Plugin Manager`](../../getting_started/configuring_chunky_launcher#plugin-manager) dialog box.

- Step 5: If you completed Step 2, then follow Steps 8 through 9. If you did not complete Step 2, then continue to Step 6.

- Step 6: The plugin should not be listed in the `Plugin Manager` dialog box. Click the `Add` button.

- Step 7: Browse for the plugin JAR file and select it.

- Step 8: The plugin should be listed in the `Plugin Manager` dialog box. Verify that the checkbox on its list entry is checked.

- Step 9: Click `Save`. The plugin will attempt to load every time Chunky is launched.

Repeat the process for any other plugins. Plugins are loaded in the order that they appear on the list. The loading order usually does not matter, but changing it can solve incompatibility problems in some cases. Read the documentations of the plugins that are being used for further information.

<div class="figure" id="figure-4-1-1">
  <p class="figure">
  Figure 4.1.1: Plugin Manager dialog box
  </p>
  <hr>
  <a href="../../img/getting_started/chunky_launcher_plugin_manager.png">
  <img class="figure" src="../../img/getting_started/chunky_launcher_plugin_manager.png" alt="Plugins Manager dialog box">
  </a>
</div>

---

--8<-- "includes/abbreviations.md"
