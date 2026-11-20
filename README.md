# Voxel Blocks

Update feed for the Voxel Blocks prototype (a Minecraft-style game built with Godot 4 and Voxel Tools).

This repository hosts game updates as [releases](../../releases). Each release contains:

- `game_vN.pck`: the game content for version N
- `manifest.json`: the version number, download URL, and SHA-256 checksum

`VoxelBlocks.exe` checks `releases/latest/download/manifest.json` at launch and every 5 minutes. When a newer version is available, it downloads and verifies the pack, saves the world, and restarts into the new version.

The game source code is not included here.
