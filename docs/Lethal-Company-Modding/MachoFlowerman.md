## Mod Concept
---
This is just another fun sound patch mod, basically patches the creatureAngerVoice and crackNeckAudio. Replacing with some fun Macho Man Randy Savage audio. 

## Pre-Development Conceptualization
---
This mod will be a bit different, as I've only patched a single SFX before (HoarderBugDonnie). This will require restructuring the way we load sounds; as it needs to be more dynamic.

One of the bigger hurdles I got over was learning what the hell an asset bundle is and how you make one. It requires Unity to build the asset bundle, and *allegedly* the AssetBundle object has to be built with the same version of Unity of the game you're modding. *I have not confirmed that last one so take it with a grain of salt.*

This is a basic outline of what an AssetBundle hierarchy looks like. It's basically a Unity zipfile... With Assets/ being at the root level. From there down, you can segregate all your sources to be references within the game code. 

![[asset_bundle_example.png]]