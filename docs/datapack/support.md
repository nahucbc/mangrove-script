# Support

Starting from version 1.13 and above, datapacks are officially supported.

## Features

1. Custom advancements
2. Custom functions
3. Custom item modifiers
4. Custom loot tables
5. Custom recipe
6. Custom world generation
7. Predicate
8. Tag

## Changelog

### 1.20.2

#### 23w31a

- Changed the pack format version to 16, accounting for sign data format changes.

#### 23w32a

- The version is now 17.

#### 1.20.2 - Pre-release 1

- The version is now 18.

### 1.20

#### 23w12a

- Changed the pack format version to 13, accounting for sign data format changes.

#### 23w16a

- Changed the pack format version to 14.

#### 23w18a

- Changed the pack format version to 15, accounting for predicate/loot table and advancement changes.

### 1.19.4

#### 23w03a

- Changed the pack format version to 11.

#### 23w06a

- Added damage types.

- Changed the pack format version to 12.

### 1.19.3

#### 22w42a

- Added a subsection called chat_type.

- Added a subsection called datapacks.

- The Vanilla world generation data pack is now visible within the game's jar.

### 1.19

#### 22w11a

- Changed the pack format version to 10.

### 1.18.2

#### 1.18.2 - Pre-release 1

- It is now possible to add custom structures in experimental data packs: the game now generates and stores data-driven configured structures.

- A lot of the cave generation is now configurable through data packs.

- Changed the pack format version to 9, due to the changes above.

### 1.18

#### 21w37a

- Changed the pack format version to 8.

### 1.17

#### 20w45a

- Pack format in version.json has been split into data and resource versions.

#### 20w46a

- Changed the pack format version to 7.

### 1.16.2

#### 20w27a

- Data packs can now have a pack.png in the root folder, and display it in the data pack menu.

#### 20w28a

- Custom worlds now support custom biomes and can now be used in custom dimension generators.

- Data packs can now customize world generation in the worldgen folder.

#### 1.16.2 - Release Candidate 1

- Changed the pack format number to 6.

### 1.16

#### 20w22a

- Slightly changed data pack loading to prevent custom data packs from crashing.

- If data pack reload fails, changes are not applied and the game continues using previous data.

- Changes to data pack list are stored only after successful reload.

- If existing data packs prevent the world from loading, the game gives an option to load the world in safe mode, which loads only vanilla data pack.

- Added --safeMode option for servers to load only with vanilla data pack.

- Game now detects any critical data pack issues, such as required tags being missing, and prevent the world from being loaded.

#### 1.16 - Pre-release 1

- Data packs can now be loaded before the world is created.

- Data packs can now add and change dimensions and dimension types.

### 1.15

#### 19w38a

- Added predicates folder where predicates can be defined.

#### 1.15 - Pre-release 1

- Changed the pack format number to 5.

### 1.14

#### 18w43a

- Tags can now be created for entity types.

### 1.13

#### 17w43a

- Added data packs.

#### 17w46a

- Added /datapack, a command to control loaded data packs.

#### 17w48a

- Data packs can now load custom recipes.

- Added the initial pack format version of 4.

#### 17w49a

- Tags can now be created with data packs.

#### 17w49b

- Tags can now be created for functions.

- Functions tagged in tick now run at the beginning of every tick.

#### 18w01a

- Added set_name function to loot tables.

- Functions tagged in load now run once after a (re)load.

- Crash reports now list what data packs are enabled.

Source: [Minecraft Fandom](https://minecraft.fandom.com/wiki/Data_pack)
