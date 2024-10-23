# Nintendo SDK Tools

A simple collection of development tools for Wii, 3DS, Wii U, and Nintendo Switch.

For complete collection of Nintendo SDK's with everything, check out [Rare Gaming Dump](https://groups.google.com/forum/#!forum/rgd-members).

Google account is required. To access Rare Gaming Dump's shared drive, click "Ask to join group", it will take a few days to have your access granted.

Dev tools are obtained from the following SDK's:

Console  | Location                                                                                                        | Size
-------- | ----------------------------------------------------------------------------------------------------------------|-----------------------------------
Wii      | `Rare Gaming Dump/Nintendo/Wii/SDK/Revolution SDK 3.3.zip`                                                      | 1.12 GiB
3DS      | `Rare Gaming Dump/Nintendo/3DS/SDKs/3DSSDK.megazarf/content/CTR_SDK-11_6_1-20180622-en.zip`                     | 4.39 GiB (megazarf), 190 MiB (zip)
3DS (NW) | `Rare Gaming Dump/Nintendo/3DS/SDKs/3DSSDK.megazarf/content/NintendoWareForCtr-3_7_6-SDK11_4_0-20170428-en.zip` | --- (same megazarf), 305 MiB (zip)
Wii U    | `Rare Gaming Dump/Nintendo/Wii U/Developer/NintendoWareForCafe-1_14_8-SDK2_13_01-20151020-en.7z`                | 400 MiB
Switch   | `Rare Gaming Dump/Nintendo/Switch/Switch SDK - [2017 - 2023]/NintendoSDK+NWv13.0.0.7z`                          | 7.26 GiB

That's 13.1 GiB total! To save your time when downloading those, I removed many extra stuff such as documents, reducing to 849 MiB.

I am not affiliated with Rare Gaming Dump in any way.

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

<details>

`CTR_FontConverter` exports fonts as `BCFNT`, a binary CTR font used in many games.

`NW_FontConverter` exports fonts as `BFFNT`, a binary Café font used in the following games:
* Mario & Luigi: Paper Jam (Bros.)
* Mario & Luigi: Superstar Saga + Bowser's Minions
* Mario & Luigi: Bowser's Inside Story + Bowser Jr.'s Journey
* Rhythm Heaven/Paradise Megamix

Not compatible with Wii U and Switch games, so use the font converter tools below instead.

</details>

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

<details>

The first 4 tools are in the `Graphics` folder, `SoundMaker` is in the `Audio` folder.

</details>

---

### Wave Audio Converter Tools
* **RVL**: `CommandLineTools` → `nw4r_waveconv.exe`
* **CTR**: `CommandLineTools` → `ctr_WaveConverter32.exe`
* **Café**: `SoundMaker` → `NW4F_WaveConverter.exe`
* **NX**: `Audio` → `AtkTools` → `WaveConverter.exe`

---

[Download (849 MiB)](https://github.com/AromaKitsune/Nintendo-SDK-Tools/releases/download/2021/Nintendo-SDK-Tools.zip)

[Mirror](https://drive.google.com/file/d/1Xc5f_Rr-nq7j7pnFwrLi0HOt_LiqYy-A/view?usp=sharing)
