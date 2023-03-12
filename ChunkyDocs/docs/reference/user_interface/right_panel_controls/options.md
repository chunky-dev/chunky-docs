---
max_chunky_version: 2_04_99
---

# Options

The `Options` tab, located in the right control panel, contains some Chunky options.

<div class="figure" id="figure-3-2-9-1">
  <p class="figure">
  Figure 3.2.9.1: The Options tab
  </p>
  <div class="figureimgcontainer">
    <a href="../../../../img/user_interface/right_panel/options_tab.png">
      <img class="figure" src="../../../../img/user_interface/right_panel/options_tab.png" alt="Options tab">
    </a>
  </div>
</div>

## Controls

- `Edit Resource Packs`: Opens the [`Resource Packs`](#resource-packs) dialog box.

- `Disable default textures (needs restart)`: Disables the textures automatically loaded by Chunky from any detected Minecraft client.jar, and reverts to Chunky's internal textures (which are not recommended), and any loaded resource packs. Chunky must be restarted for changes to take effect.

- `Single color textures (needs restart)`: Changes block textures to a single color which is the average of the colors on each pixel on the texture of the block. Contrary to the name of the control, Chunky need not be restarted for changes to take effect. This error was fixed in the [Stable snapshot](../../../../getting_started/configuring_chunky_launcher#advanced-settings) release.

- `Show launcher when starting Chunky`: Changes whether the Chunky launcher is shown when starting Chunky. It is recommended that this remain enabled.

- `Open Scenes Directory`: Opens the directory to which Chunky saves scenes.

- `Change Scenes Directory`: Opens the [`Scene Directory Picker`](#scene-directory-picker) dialog box.

## Resource Packs

The `Resource Packs` dialog box, shown in [Figure 3.2.9.2](#figure-3-2-9-2), displays a list of currently-loaded resource packs along with some management controls at the bottom.

<div class="figure" id="figure-3-2-9-2">
  <p class="figure">
  Figure 3.2.9.2: Resource Packs dialog box
  </p>
  <div class="figureimgcontainer">
    <a href="../../../../img/user_interface/right_panel/resource_packs.png">
      <img class="figure" src="../../../../img/user_interface/right_panel/resource_packs.png" alt="Resource Packs dialog box">
    </a>
  </div>
</div>

A resource pack in the list can be clicked to select it.

- `Up`: Moves the selected resource pack above the resource pack that is immediately above it.

- `Down`: Moves the selected resource pack below the resource pack that is immediately below it.

- `Add`: Opens a file explorer dialog box to browse for a ZIP file, JAR file, or pack.mcmeta file for Chunky to load as a resource pack.

- `Remove`: Removes the selected resource pack from the list.

- `Apply`: Applies the new resource pack configuration as the default and closes the `Resource Packs` dialog box.

## Scene Directory Picker

The `Scenes Directory Picker` dialog box, shown in [Figure 3.2.9.3](#figure-3-2-9-3), allows the directory in which Chunky stores scenes to be changed.

<div class="figure" id="figure-3-2-9-3">
  <p class="figure">
  Figure 3.2.9.3: Scene Directory Picker dialog box
  </p>
  <div class="figureimgcontainer">
    <a href="../../../../img/user_interface/right_panel/scene_directory_picker.png">
      <img class="figure" src="../../../../img/user_interface/right_panel/scene_directory_picker.png" alt="Scene Directory Picker dialog box">
    </a>
  </div>
</div>

- `Browse`: Opens a file explorer dialog box to browse for a directory to which Chunky should save scenes. Alternatively, type the folder path in the input field to the left.

- `Create this directory`: Enables or disables the creation of the directory (folder) specified in the input field above upon clicking `Ok`. This control only appears if the folder specified by the path typed in the input field does not exist.

- `Ok`: Exits the dialog box and applies any changes made.

- `Cancel`: Exits the `Scene directory picker` dialog box without applying any changes made.

--8<-- "includes/abbreviations.md"
