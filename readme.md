### Emissive textures for a variety of common forge mods.
#### Emissive support added to:
- Chisel
- Xtones
- Applied Energestics 2

#### Texture updates applied to:
- Applied Energestics 2 : Will now use the more modern, white looking textures from newer versions

#### Addon packs:
- Borderless Antiblock
- Functionally Less Glow
- Factorio Sound Pack

#### Will support:
- Gregtech Community Edition Unofficial (with ZedTech installed).
- Avaritia
- Deep Mob Learning/Evolution
- Ender IO
- Vanilla

Need help? Want to share cool screenshots? Join the [Discord](https://discord.gg/8aZ4TpdPWZ).

### Notes about compatability
1. This pack explicitly supports Optifine on 1.12.2, and 1.7.10 without interpolation (not the end of the world). This pack will not work on anything 1.13+.

2. You should set `Old Lighting: ON` in the optifine shading menu, so blocks with custom renderer's (like architecturycraft) correctly display texture colours.

3. censoredASM `onDemandAnimatedTextures=true` makes textures only animate when observed, but doesnt apply to gtceu's glowing texture layer, causing textures to "desync", where the glowing layer doesnt follow the texture layer. Edit `.minecraft/config/loliasm.cfg` and change its value to `false.`

4. LittleTiles requires mipmapping to be enabled in any form if optifine is installed. PBR Mapping and mipmaps do not go well together. Resource Packer will eventually generate proper mipmaps that dont look like garbage, but this will make stuff look weird at a distance. This effect is most visible on the ME Controller

5. \* This pack will probably work on 1.13+ for some mods, if you rename all folders named blocks/particles/items to block/particle/item. 

Notice for mod authors:
	Some textures from mods/texturepacks are selectively included in this resource pack to ensure overlay conflicts & weird stuff doesnt happen. If you have an issue with this, contact me in the aforementioned discord server.
