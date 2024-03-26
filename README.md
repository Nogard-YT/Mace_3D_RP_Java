
# Mace 3D RP
This resource pack enhances the Mace by giving it a 3D model! The Mace is a new weapon added to Minecraft Java Snapshot 24W11A. For consistency reasons, Mojang decided to make the Mace a 2D item. However, many people wish it had a 3D model instead. Which is the reason, why I created this resource pack. And I made it for both Minecraft universes - [Bedrock](https://github.com/Nogard-YT/Mace_3D_RP_Bedrock) and Java!

Creator: **Nogard** ([Twitter](https://twitter.com/Nogard_YT), 
[YouTube](https://www.youtube.com/channel/UCPjuDppuSBB2fRiTl9UOQ5Q?sub_confirmation=1), 
[Reddit](https://www.reddit.com/user/Nogard_YT/), 
[Facebook](https://fb.me/Nogard.YT))  

![Mace](https://github.com/Nogard-YT/repo/blob/main/Mace_3D_RP_Java/images/key_art_mcpedl.png)

## A new weapon - the Mace
Mace is a truly high-risk, high-reward weapon. It can deal crazy amounts of damage, but only if you time things perfectly. For example, you need to land from a height of 100 blocks to kill Warden on a single hit. And that's not all; if you manage to actually hit the mob before landing, you won't take any fall damage. Doesn't that sound completely insane already? Well, guess what, you can kill Wither and Ender Dragon on a single hit too! But ummm, don't forget to bring some totems of undying for the missed attempts, hehe.

![Mace](https://github.com/Nogard-YT/repo/blob/main/Mace_3D_RP_Java/images/ender_dragon_elytra.png)

Mace was introduced in [Snapshot 24W11A](https://www.minecraft.net/en-us/article/minecraft-snapshot-24w11a) to Minecraft Java, and in [Minecraft Bedrock Beta & Preview - 1.20.80.22](https://www.minecraft.net/en-us/article/minecraft-preview-1-20-80-22), both released on March 14th, 2024. Therefore, it's essential to be on either of these versions or higher respectively to be able to use this resource pack. Additionally, don't forget to turn on experiments for your world. In Minecraft Java you can enable them under "More" tab when creating a world. Then under "Experiments" button, where you can toggle "Update 1.21" on. 

![Mace](https://github.com/Nogard-YT/repo/blob/main/Mace_3D_RP_Java/images/screenshot.png)

## Why is it not 3D by default?
There undoubtedly are some technical constraints, which might have led Mojang to make the Mace a 2D item instead of creating a 3D model for it. One of these might be the player swiping animation on Bedrock, as it requires changes in player animation files to make it look like an actual weapon. Another could be an enchantment layer material and render controller for attachables. But mainly, I believe it's because all the weapons in Minecraft have always been 2D, so it wouldn't make much sense to make the new weapon 3D. And I do agree with Mojang on this. Despite that, I personally find it look way better when it's 3D, and I'm sure that many players will agree with me as well.

![Mace](https://github.com/Nogard-YT/repo/blob/main/Mace_3D_RP_Java/images/2d_to_3d.png)

Even the Java version of this resource pack is available in two types. The first option (recommended) exclusively adds a 3D model to the Mace. Which means that it will be compatible with just Snapshot 24W11A or higher.  
However, I aimed to allow players on older versions to enjoy the Mace as well. Therefore, I created the second version, which integrates the Mace as custom model data of a stone sword, as well as it still makes the vanilla Mace 3D. This way, you can use the 3D Mace on any version of Minecraft Java. Keep in mind, that it's solely a resource pack, so don't expect the Mace functionality to work on versions prior to Snapshot 24W11A. Generally, speaking it's recommended to download the first version.  

## Custom Model Data
In case you opt to download the second version of the resource pack, you can use the following custom model data numbers to obtain the Mace in your world.  

### Format  
```yml
custom_item_name
vanilla_item_override: custom_model_data_number
command: give_command
new_command: give_command (Snapshot 24w12a and higher)
```

### List
```yml
mace_2d (vanilla)
stone_sword: 1
command: /give @s stone_sword{CustomModelData:1}
new_command: /give @s stone_sword[custom_model_data=1]

mace_3d (custom)
stone_sword: 2
command: /give @s stone_sword{CustomModelData:2}
new_command: /give @s stone_sword[custom_model_data=2]
```

## License Terms
You're allowed to record videos and take screenshots of this work. You may share this work with others, but only with the original download link. You're allowed to use this work in your Minecraft worlds and servers without any limitations. However, redistribution without author's consent in applications, websites, and other media, as well as earning money from it, will be punished by law. 

**Nogard**

Contacts: 
Email: nogmcpe@gmail.com  
Discord: Nogard#9634 (nogcube)  
Twitter: [@Nogard_YT](https://twitter.com/@Nogard_YT)

## Intallation (Minecraft Java)
1. Download the resource pack `.zip` archive.
2. Add the archive into `.minecraft/resourcepacks` folder.
5. Enable the `Mace_3D_RP.zip` in the world or global settings.
6. Enjoy! (You can extract the archive as well, instead of using `.zip`.)  

## Download
Mace 3D RP (recommended): https://github.com/Nogard-YT/Mace_3D_RP_Java/releases/tag/v1.0.0  
Mace 3D RP (custom model data): https://github.com/Nogard-YT/Mace_3D_RP_Java/releases/tag/v1.0.0_custom_model_data  

Minecraft Bedrock version: https://github.com/Nogard-YT/Mace_3D_RP_Bedrock/releases/tag/v1.0.0  
