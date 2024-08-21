# godot_finder_bin

binary repository of [godot_finder](https://github.com/funatsufumiya/godot_finder)

if you need `godot_finder` [releases](https://github.com/funatsufumiya/godot_finder/releases) as `git submodule`, please use this repository.

## Simple usage example

```bash
cd PROJECT_DIR_OF_YOUR_GODOT
cd addons
git submodule add https://github.com/funatsufumiya/godot_finder_bin.git finder
# or simply: git clone https://github.com/funatsufumiya/godot_finder_bin.git finder
```

but I recommend to use `godotenv addons install`. see [GodotEnv's readme](https://github.com/chickensoft-games/GodotEnv?tab=readme-ov-file#initializing-godotenv-in-a-project). GodotEnv's `addons.jsonc` config is below (partial):

```json
    "finder": {
      "url": "https://github.com/funatsufumiya/godot_finder_bin",
      "checkout": "v0.1.3",
    },
```

