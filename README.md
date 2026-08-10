# 🗣️ Blender Lip Sync Addon

Official Documentation: [https://docs.cgpoly.io](https://docs.cgpoly.io/lip-sync-documentation)

A **Blender addon** for automatic lip-syncing based on audio input.  
Cross-platform (Windows, macOS, Linux), works **out of the box** with **~25 languages**.

https://github.com/user-attachments/assets/cb90ea7b-02fc-4ca1-b19f-631024cd79cd

https://private-user-images.githubusercontent.com/71397668/633415515-aee2a486-6aaf-4275-9ce6-bb961860f8ea.mp4

## ✨ Features

- 🎤 Converts voice audio into animated mouth shapes
- Interpolates between Shape Key to give natural lips motion
- 🖼️ Projects a viseme **spritesheet** onto your character’s face (one spritesheet is shipped with the add-on, but you can use your own)
- 🧠 Uses offline speech recognition (Vosk + Phonemizer + eSpeak)
- 🖥️ Fully tested on Windows, macOS and Linux
- 🔜 Future upgrade: **Pose-based animation** for facial rigs

## 📦 Installation
<img width="857" height="597" alt="image" src="https://github.com/user-attachments/assets/09db1b2c-173a-4e3a-bc0e-513e327be0bd" />

1. Download file iocgpoly_lip_sync-2.3.2-windows_x64.zip in https://github.com/guen-studio/lip-sync/releases/tag/Blender.
2. Open Blender.
3. Go to **Edit > Preferences > Add-ons > Install from Disk...**
4. Look for **iocgpoly_lip_sync-2.3.2-windows_x64.zip** and click **Install from Disk**

When you select a Language Model for the first time, Model file is downloaded and cached for future uses  (~40Mo, depending on the language).

## 🛠️ How to Use (Spritesheet)

1. Import or create a 3D character.
2. Add your movie / sound clip in Video Sequencer
3. Go to the **Lip Sync** tab in the **N-panel**.
4. Select your Language among 30 available languages.
5. Click **Add Spritesheet on Selection** 
6. Click **Set Mouth Area** from **Edit Mode**
7. Click **Analyze Audio** and wait few seconds – your character now speaks!

## 🐞 Known Issues

- Characters require no rotation and applied Scale

## 🧩 Tested

- Blender **5.2** for **Windows**

## 📜 License

This project is licensed under the [GNU General Public License v3.0 or later](https://spdx.org/licenses/GPL-3.0-or-later.html).

---

Thanks to [Charley 3D](https://github.com/charley3d)
