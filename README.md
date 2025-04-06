# Aurelia PS Vita Port

![Aurelia Game Screenshot](https://cdn.discordapp.com/attachments/1300402299356844053/1358403080223199272/header.jpg?ex=67f3b6f4&is=67f26574&hm=d01357659e73c0dbcc05254cf35840b6b5b085f39cfe0d99000affb36b1f76ad&)


This is a port of Aurelia (version 27.1) to the PlayStation Vita. The game runs at a stable 60 FPS. It is technically possible to port all versions of the game up till version 28 because they all use the GMS engine.

📝 Important Notes 📝

- The game has around 1-2 framedrops when it first loads or renders a new area but then it stabilizes at 60 FPS
- The port runs on Aurelia V 27.1
- The installation of the game's .vpk file will take around 10-15 minutes to complete
- The game uses the touch-screen controls & utilizes the right analog stick & the circle button to mimick a mouse input similar to that on PC ([You can map some controls to the physical buttons by creating a keys.ini file in the game directory](https://gist.github.com/CatoTheYounger97/ce19685d349d913f9a2f097464453c97))


📋 Prerequisites 📋 

• Install [kubridge](https://github.com/TheOfficialFloW/kubridge/releases/) and [FdFix](https://github.com/TheOfficialFloW/FdFix/releases/) by copying kubridge.skprx and fd_fix.skprx to your taiHEN plugins folder (it's either located in ux0:tai or ur0:tai) and adding two entries to your config.txt under *KERNEL:
1) For tai folder located in ux0
 ```plaintext
  *KERNEL
  ux0:tai/kubridge.skprx
  ux0:tai/fd_fix.skprx
```
2) For tai folder located in ur0
```plaintext
  *KERNEL
  ur0:tai/kubridge.skprx
  ur0:tai/fd_fix.skprx
```
📜 Note: Don't install fd_fix.skprx if you're using the rePatch plugin.

• Install [libshacccg.suprx](https://samilops2.gitbook.io/vita-troubleshooting-guide/shader-compiler/extract-libshacccg.suprx), if you don't have it already, by following this guide.

📥 Installation 📥

1) Download the Aurelia PS Vita port .vpk file from this repository. 🔽
2) Install the .vpk file on your PS Vita. 🖥️
3) Launch the game from the LiveArea. 🎮


📜 Performance Tip: It is recommended to overclock the PS Vita’s CPU and GPU to achieve the best performance.


⌨️ Controls ⌨️

- Touchpad: Use the touchpad to navigate menus and control in-game movement. 👆


🐞 Known Issues 🐞

- Touch controls can sometimes act out and register unintended presses

- Right Analog Sensitivity is too high

- Initial 1-2 frame drops when first launching/loading the game or a new area, then it stabilizes at a smooth 60 FPS. 🚀


⚠️ Disclaimer ⚠️

By downloading this game port, you acknowledge that you own a legal copy of the original game, which was purchased from the original developer of the game or an authorized retailer. This port is NOT intended to promote or be any form of piracy 🚫. It is simply an attempt to bring the game to the PlayStation Vita for personal, non-commercial use. The goal is to support the game,its developer, and help those who already own the game enjoy it on a different platform (other than PC & Android).

Please respect the rights of the developers and follow the laws regarding software usage in your region. 📜


🏆 Credits 🏆

- [Mirthal](https://www.mirthal.com/) – the original developer of Aurelia. 💻
- NFSHubster – for porting the game to the PS Vita. 🎮
- Community – for their contributions and support. 🌍


📜 License 📜

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
. 📑


