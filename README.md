# mhp2g-texture-pack
Custom Textures for Monster Hunter Freedom Unite Complete [FUC](https://fucomplete.github.io/) / Portable 2nd G (ULJM05500)

## 👁️ Overview
![2025-04-23_09-33](https://github.com/user-attachments/assets/44517f1c-cd21-4334-af4f-5e3bd6ccc194)
![2025-04-23_09-32](https://github.com/user-attachments/assets/ab3fba51-0b30-45b7-8685-21ec241c200f)
![2025-04-23_09-28](https://github.com/user-attachments/assets/23c55a39-171a-4b03-8493-d5691f0b9e34)

# 🎮 Monster Hunter Portable 2nd G - FUC (Patched) - Texture Pack
This project contains a custom texture pack for the game **Monster Hunter Portable 2nd G - [FUC (Patched)](https://fucomplete.github.io/)**, compatible with the **PPSSPP** emulator.

## 📥 Download
The texture pack is available in the [**Releases**](../../releases) section of the repository, due to its size (1.5GB).

> ⚠️ Do not use the "Code > Download ZIP" button, as it does not include the large files hosted in the Releases.



## 🧾 Installation

1. Extract the file: `ULJM05500.zip`.
2. Copy or move the folder: `ULJM05500` to: `Memstick/PSP/TEXTURES`.
3. Open **PPSSPP**, go to `Settings > Tools > Developer Tools > Replace Textures ✅`.

✨**Done! The custom textures will be active in the game.** 😄🎮



### 🎨 Options and Extras

Feel free to modify the `texture.ini` file as you wish — but there are some specific options/changes you can make to truly make it your own.

---

#### 1. Introduction screen

There are two available options for the intro screen:

- **Default (enabled):**  
  **Monster Hunter Freedom Unite Complete**

  ![INTRO_FUC](https://github.com/user-attachments/assets/3f51664f-812d-4920-aad3-17077dd1bca2)

- **Alternative (original version - ULJM05500):**  
  **Monster Hunter Portable 2nd G**

  ![INTRO_P2G](https://github.com/user-attachments/assets/d87707d7-670f-4665-827f-3b81d47bf5c2)

***

Look for the section that contains `"Intro Screen"` in the `texture.ini` file and remove the `#` to the following variable to match your preferred option:

```ini
#========================================
#		Intro Screen
#
#	Default = Bar/FUC.png
#	Portable 2nd G = Bar/P2G.png
#========================================
000000007c963d08bcffe946 = Bar/FUC.png # Default (enabled)
#000000007c963d08bcffe946 = Bar/P2G.png # Alternative (original version - ULJM05500)
```


#### 2. Resource Map

By default, the game map does not provide any help regarding the items you can pick up. Everything needs to be explored and, in a way, memorized 😅
To enable the resource map, within the `texture.ini` file, look for the `"Optional Resource Map"` section and change the variable path as follows:

```ini
#==================================================================
#                                               Optional Resource Map
#
#       For enable the resource map just change the path below, example:  
#        "variable = DefaultMapHUD/..." for "variable = ResourceMap/..."
#
#
#==================================================================
0419c2004b3da8487bfa45cc = ResourceMap/0419c2004b3da8487bfa45cc.png
0419c200688906efecd8bddf = ResourceMap/0419c200688906efecd8bddf.png
0419c20063448d71ee89dfc3 = ResourceMap/0419c20063448d71ee89dfc3.png
0419c20010382eac257f9c03 = ResourceMap/0419c20010382eac257f9c03.png
0419c20010286fc6311b5f16 = ResourceMap/0419c20010286fc6311b5f16.png
0419c20008032c5db408c2ad = ResourceMap/0419c20008032c5db408c2ad.png
0419c20086e35b013e17a185 = ResourceMap/0419c20086e35b013e17a185.png
0419c2008bce426fd6440a2f = ResourceMap/0419c2008bce426fd6440a2f.png
0419c200fb2fd024cbd54ffb = ResourceMap/0419c200fb2fd024cbd54ffb.png
0419c200bd81d98e48a98a7e = ResourceMap/0419c200bd81d98e48a98a7e.png
0419c200ea98fcf415718085 = ResourceMap/0419c200ea98fcf415718085.png
0419c200ce016a386a28cc7b = ResourceMap/0419c200ce016a386a28cc7b.png
0419c200ce016a3830ba0418 = ResourceMap/0419c200ce016a3830ba0418.png
0419c200d647f218988de085 = ResourceMap/0419c200d647f218988de085.png
0419c200f426e25c17fa079f = ResourceMap/0419c200f426e25c17fa079f.png
0419c2006b1d306c6ef914b7 = ResourceMap/0419c2006b1d306c6ef914b7.png
0419c2006b1d306c8020fb09 = ResourceMap/0419c2006b1d306c8020fb09.png
```
