<h3 align="center"><img alt="logo" height="500px" src="https://raw.githubusercontent.com/anonymouseMC/emissive-glowing-forge/master/pack.png"/></h3>
<h3 align="center">Emissive textures for a variety of common forge mods.</h3>

#### Emissive support added to:
- Chisel
- Xtones
- Applied Energistics 2
- Avaritia
- Deep Mob Learning/Evolution

#### Texture updates applied to:
- Applied Energistics 2 : Will now use the modern, white looking textures from newer versions.
- Applied Energestics 2 : Updated drive lights to match the emission wavelengths of Red, Orange, and Green LED's (750nm, 630nm, 555nm).

#### Addon packs:
- Borderless Antiblock
- Functionally Less Glow
- Factorio Sound Pack

#### Will support:
- Gregtech Community Edition Unofficial (with [ZedTech](https://github.com/CosmicNovaStar/Zederrian-Technology-GTCEu) installed). (Thanks for the script goes to [Aproxia](https://modrinth.com/resourcepack/egregious-emissives)
- Ender IO
- Vanilla
- Modified fork of BSL with a not-clamped dynamic range, and an expanded bloom strength

Need help? Want to share cool screenshots? Join the [Discord](https://discord.gg/8aZ4TpdPWZ).

### Notes about compatability
1. This pack explicitly supports Optifine on 1.12.2, and 1.7.10 without interpolation (not the end of the world). This pack will not support anything 1.13+.

2. You should set `Old Lighting: ON` in the optifine shading menu, so blocks with custom renderer's (like architecturycraft) correctly display texture colours.

3. censoredASM `onDemandAnimatedTextures=true` makes textures only animate when observed, but doesnt apply to gtceu's glowing texture layer, causing textures to "desync", where the glowing layer doesnt follow the texture layer. Edit `.minecraft/config/loliasm.cfg` and change its value to `false.`

4. LittleTiles requires mipmapping to be enabled in any form if optifine is installed. PBR Mapping and mipmaps do not go well together. Resource Packer will eventually generate proper mipmaps that dont look like garbage, but this will make stuff look weird at a distance. This effect is most visible on the ME Controller

5. \* This pack will probably work on 1.13+ for some mods, if you rename all folders named blocks/particles/items to block/particle/item. 

Notice for mod authors:
	Some textures from mods/texturepacks are selectively included in this resource pack to ensure overlay conflicts & weird stuff doesnt happen. If you have an issue with this, contact me in the aforementioned discord server.
