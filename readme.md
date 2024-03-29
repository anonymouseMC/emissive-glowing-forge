<h3 align="center"><img alt="logo" height="500px" src="https://raw.githubusercontent.com/anonymouseMC/emissive-glowing-forge/master/pack.png"/></h3>
<h3 align="center">Emissive textures for a variety of common forge mods.</h3>
<h4 align="center"><a href="https://codeload.github.com/anonymouseMC/emissive-glowing-forge/zip/refs/heads/master">Download</a></h4>

<details>
  <summary>Examples</summary>

  <img height="500px" src="https://raw.githubusercontent.com/anonymouseMC/emissive-glowing-forge/master/examples/gtceu_lamps.png" />
  <img height="500px" src="https://raw.githubusercontent.com/anonymouseMC/emissive-glowing-forge/master/examples/ae2_drive_lights.png" />

</details>

#### Emissive support added to:
- Gregtech Community Edition Unofficial (with [ZedTech](https://github.com/CosmicNovaStar/Zederrian-Technology-GTCEu) installed). (Thanks for the script goes to [Aproxia](https://modrinth.com/resourcepack/egregious-emissives))
- Chisel
- Xtones
- Applied Energistics 2
- Avaritia
- Deep Mob Learning/Evolution

#### Texture updates applied to:
- Applied Energistics 2 : Will now use the modern, white looking textures from newer versions.
- Applied Energestics 2 : Updated drive lights to match the emission wavelengths of Red, Orange, and Green LED's (750nm, 630nm, 555nm).
- GTCE-U : Orange & Yellow lamps have had their colours changed to represent the spectra emitted by LPS and HPS lamps.

#### Addon packs:
- <a href="https://github.com/anonymouseMC/borderless-antiblock">Borderless Antiblock</a>
- <a href="https://github.com/anonymouseMC/factorio-sound-pack">Factorio Sound Pack</a>

#### Will support:
- Ender IO
- Vanilla

Need help? Want to share cool screenshots? Join the [Discord](https://discord.gg/8aZ4TpdPWZ).

### Notes about compatability
1. This pack explicitly supports Optifine on 1.12.2, and 1.7.10 without interpolation (not the end of the world). This pack will not support anything 1.13+.

2. You should set `Old Lighting: ON` in the optifine shading menu, so blocks with custom renderer's (like architecturycraft) correctly display texture colours.

3. censoredASM `onDemandAnimatedTextures=true` makes textures only animate when observed, but doesnt apply to gtceu's glowing texture layer, causing textures to "desync", where the glowing layer doesnt follow the texture layer. Edit `.minecraft/config/loliasm.cfg` and change its value to `false.`

4. LittleTiles requires mipmapping to be enabled in any form if optifine is installed. PBR Mapping and mipmaps do not go well together. Resource Packer will eventually generate proper mipmaps that dont look like garbage, but this will make stuff look weird at a distance. This effect is most visible on the ME Controller

5. \* This pack will probably work on 1.13+ for some mods, if you rename all folders named blocks/particles/items to block/particle/item. 

