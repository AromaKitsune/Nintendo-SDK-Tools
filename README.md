# Nintendo SDK Tools

A simple collection of development tools for Wii, 3DS, Wii U, and Nintendo Switch.

I am not affiliated with Nintendo in any way.

We also have a [backup page on Rentry](https://rentry.co/Nintendo-SDK-Tools) - make sure to bookmark it! :)

---

### Revolution - Wii
* 3DEditor
* EffectMaker
* LayoutEditor
* NW4R_fontcvtr
* SoundMaker

---

### CTR - 3DS
* CTR_FontConverter
* NW4C_3DEditor
* NW4C_SoundMaker
* NW_EffectMaker
* NW_FontConverter
* NW_LayoutEditor
* PCViewer

`CTR_FontConverter` exports fonts as `BCFNT`, a binary CTR font used in many games.

`NW_FontConverter` exports fonts as `BFFNT`, a binary Café font used in the following games:
* Rhythm Heaven Megamix (US) / Rhythm Paradise Megamix (EU)
* Mario & Luigi: Paper Jam (US) / Mario & Luigi: Paper Jam Bros. (EU)
* Mario & Luigi: Superstar Saga + Bowser's Minions
* Mario & Luigi: Bowser's Inside Story + Bowser Jr.'s Journey

Not compatible with Wii U and Switch games, so use the font converter tools below instead.

---

### Café - Wii U
* NW4F_3DEditor
* NW4F_FontConverter
* NW4F_LayoutEditor
* NW4F_SoundMaker
* NW_EffectMaker

---

### NX - Nintendo Switch
* 3DEditor
* EffectMaker
* FontConverter
* LayoutEditor
* SoundMaker

The first 4 tools are in the `Graphics` folder, `SoundMaker` is in the `Audio` folder.

---

### Wave Audio Converter Tools
* **RVL**: `CommandLineTools` → `nw4r_waveconv.exe`
* **CTR**: `CommandLineTools` → `ctr_WaveConverter32.exe`
* **Café**: `SoundMaker` → `NW4F_WaveConverter.exe`
* **NX**: `Audio` → `AtkTools` → `WaveConverter.exe`
