Emissive textures for a variety of common forge mods running on 1.12.2, probably also support 1.7.10. Will not support anything past 1.13*
Emissive support added to:
- Chisel
- Xtones
- Applied Energestics 2

Texture updates applied to:
- Applied Energestics 2 : Will now use the more modern, white looking textures from newer versions

Addon packs:
- Borderless Antiblock
- Functionally Less Glow
- Factorio Sound Pack

Will support:
- Gregtech Community Edition Unofficial (with ZedTech installed).
- Avaritia
- Deep Mob Learning/Evolution
- Ender IO
- Vanilla

Need help? Want to share cool screenshots? Join the [Discord](https://discord.gg/8aZ4TpdPWZ).

___Notes about compatability___
**censoredASM `onDemandAnimatedTextures=true` makes textures only animate when observed, but doesnt apply to gtceu's glowing texture layer, causing textures to "desync", where the glowing layer doesnt follow the texture layer. Edit `.minecraft/config/loliasm.cfg` and change its value to `false.`**

**LittleTiles requires mipmapping to be enabled in any form if optifine is installed. PBR Mapping and mipmaps do not go well together. Resource Packer will eventually generate proper mipmaps that dont look like garbage, but this will make stuff look weird at a distance. This effect is most visible on the ME Controller**

\* This pack will probably work on 1.13+ for some mods, if you rename all folders named blocks/particles/items to block/particle/item. 

Notice for mod authors:
	Some textures from mods/texturepacks are selectively included in this resource pack to ensure overlay conflicts & weird stuff doesnt happen. If you have an issue with this, contact me in the aforementioned discord server.
