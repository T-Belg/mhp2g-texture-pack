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
***

#### 2. Resource Map

The resource map is there to help you explore. Through it, you can find out what items appear in each area, saving you time and patience spent walking in circles 😅

> By default, the game map does not provide any help regarding the items you can pick up. Everything needs to be explored and, in a way, memorized.

| Default | Resource Map enabled | 
|------------|------------------|
| ![2025-04-23_10-30](https://github.com/user-attachments/assets/e79c26a0-43ce-4939-92fb-c66308d01ccd)  | ![2025-04-23_10-36(1)](https://github.com/user-attachments/assets/0f0c42bb-4f8e-4b3e-942c-f97767b2123f)|


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
***

#### 3. Buttons 

This is one of the parts I like the most, changing the game's buttons.

Again, all editing is done through the `texture.ini file`, so open it and look for the `"Optional UI Buttons"` section. Now change the path of the variables to the way you like the most.

```ini
#=================================================================================================
#                                               Optional UI Buttons
#
# 		To change the layout of the UI buttons, simply change the path below, for example:
# 			"variable = Bar/SBar3.png" to "variable = Bar/SBarNPS.png"
#
#
#		Where: 
#		SBarNPS = New bar with PlayStation buttons layout
#		SBarNX = New bar with Xbox buttons layout
#		SBarNX2 = New bar with Xbox buttons layout variation
#		SBarN = New bar
#		SBarNPS2 = Is default bar with PlayStation modern look variation
#		SBarNPS3 = Is default bar with PlayStation modern look variation
#
#		
#=================================================================================================
00000000af1e2872ddeab148 = Bar/SBarNX.png
09156ba0e580c2a8cc4477b1 = Bar/SBarNX.png
09156ba0e580c2a8e299e153 = Bar/SBarNX.png
00000000af1e2872ddeab148 = Bar/SBarNX.png
00000000af1e2872ddeab148 = Bar/SBarNX.png
```

See the variations:
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/72924858-728f-4e7d-b59d-aaf6d4645e42" width="300">
</p>
***SBarNX2***

![SBarNX2](https://github.com/user-attachments/assets/28b8dd03-00fb-477a-86bf-5ab03c5da94f)

***SBarN***

![SBarN](https://github.com/user-attachments/assets/610cd32a-a9f2-4ffc-bc6a-b8f3bb7bb34e)

***SBarNPS***

![SBarNPS](https://github.com/user-attachments/assets/0ea6b6d8-1a6c-4d8e-88b6-7b1d5eaf5886)

***SBarNPS2***

![SBarNPS2](https://github.com/user-attachments/assets/e23cba21-5e0b-4c7a-b43e-c67dc1c879a8)

***SBarNPS3***

![Novo Projeto(1)](https://github.com/user-attachments/assets/69a360fd-d340-4785-af00-632e37fe1e74)



