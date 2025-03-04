# Laser-Tag-Free4All

Simple modification of [Flipper-Zero-Laser-Tag](https://github.com/RocketGod-git/Flipper-Zero-Laser-Tag) that removes teams and makes everyone play solo.

## 🚀 Real World Free for all Laser Tag game

Use Flipper Zero as your laser blaster, RFID scan for power-ups, and automatic detection of add-on weapons to GPIO such as the Rabbit Labs Masta-Blasta for arena style play.

### ⚡ Key Features:

- **Real-Time Gameplay**: Smooth and responsive laser firing and hit detection.
- **Immersive Sound**: Laser firing and game-over sounds to enhance your battlefield experience.
- **Dynamic Health and Ammo Bars**: Keep track of your health and ammo with clean, dynamic UI elements.
- **Vibration Feedback**: Feel every hit with integrated vibration feedback.
- **RFID Powerups**: Specific tags can be written to any T5577 or EM4100 for adding ammo.
- **External IR Boards**: Add or remove an external infrared blaster anytime during gameplay to switch between internal/external IR gun or swap weapons.

## 📸 Screenshots

![Screenshot-20240823-224628](https://github.com/user-attachments/assets/5836ee25-23ce-4845-b342-2b360e32e341)
![Screenshot-20240823-224637](https://github.com/user-attachments/assets/119e8e80-49fc-421a-bc61-ec7185d05bc0)
![Screenshot-20240823-224647](https://github.com/user-attachments/assets/d5e10e1b-64a5-4a72-a624-2cfe2237add5)

## 🕹️ How to Play

1. **Start gameplay**: Press the OK button to enter the game.
2. **Fire Your Laser**: Press the OK button to shoot your laser at your opponents.
3. **Reload**: When your ammo runs out, press 'Down' to reload and get back into action.
4. **Survive**: Track your health, and make sure to avoid getting hit by your opponents' lasers. If your health reaches zero, it's game over!

## 🏅 Current Powerups for RFID Tags (T5577/EM4100):

- **Ammo Refill**: `13 37 00 FD 0A` – Increases ammo by `0x0A` for any player.

_Tip_: You can modify the last byte (e.g., `0A`) to change the amount of ammo refilled. Stay tuned for future updates and new powerups!
