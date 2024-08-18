# vrchat-ndmf-template-project

A VRChat NDMF Based Avatar Template Project

based on modules listed at <https://github.com/Spokeek/awesome-ndmf>

## Requirements

This template is based on NDMF modules that aren't available out of the box in VCC/ALCOM

You will need to install the following repositories.
For more details, check <https://github.com/Spokeek/awesome-ndmf>

- Nadena (Modular Avatar/ndmf) <https://modular-avatar.nadena.dev>
- Rs64 (TexTransTool) <https://ttt.rs64.net>
- Anatawa (Avatar-Optimizer) <https://vpm.anatawa12.com/avatar-optimizer/en>
- Dreadscripts (Hierachy Plus) <https://vpm.dreadscripts.com>
- Narazaka (avatar-menu-creater-for-ma) <https://narazaka.github.io/AvatarMenuCreaterForMA>
- Hai (Prefabulous) <https://docs.hai-vr.dev/docs/products/prefabulous-avatar>

If you are using the [ALCOM Package manager](https://vrc-get.anatawa12.com/alcom/), you can install all the missing repositories by importing the [repositories.txt](repositories.txt) file in your repository list.

## How to add as a template

### If you have git installed

- Run the command `git clone https://github.com/Spokeek/vrchat-ndmf-template-project "%appdata%\..\local\VRChatCreatorCompanion\Templates\NDMF_Template"`

- You are done

### If you don't have git

- Download this project as a zip file

- Open the path `%appdata%\..\local\VRChatCreatorCompanion\Templates` in Windows Explorer

- Extract the project to obtain a new project folder in the previously opened folder

- You are done

### Auto Update

There is a github workflow updating dependencies every day so the project is always up to date.

See the file at [update-vpm-dependencies.yml](.github/workflows/update-vpm-dependencies.yml)

Thank you to @anatawa12 for the cool vrc-get project and actions associated.

## How to contribute

- Clone the repository at your desired path

- run the following command as administrator `mkdir /d "%appdata%\..\local\VRChatCreatorCompanion\Templates\NDMF_Template" "You_Path_To_Your_Local_Project"`
