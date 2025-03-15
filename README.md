# 🕹️ 2048 Game - Console Version  

## 📌 About the Game  
This is a **console-based** implementation of the classic **2048 game**, written in **C**.  
The goal of the game is to **slide and merge tiles** to reach the **2048 tile**.  

## 🎮 How to Play  
* The game board consists of a **4x4 grid**.  
* Use the following **commands** to move the tiles:  
  - **`w`** → Move Up  
  - **`s`** → Move Down  
  - **`a`** → Move Left  
  - **`d`** → Move Right  
  - **`n`** → Start a New Game  
  - **`q`** → Quit the Game  
* When two tiles with the same number collide, they **merge into one**.  
* The game ends when there are **no more possible moves**.  

## 🛠 Installation & Running the Game  

### **1️⃣ Clone or Download the Repository**  
Run the following command in the terminal to clone the repository:  

```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/2048-Game.git
cd 2048-Game
```
Alternatively, download the ZIP file and extract it.

## **2️⃣ Compile & Run (Windows)**
Open a C compiler such as MinGW (GCC) or Turbo C++.

Compile the code using GCC:
```sh
gcc 2048.c -o 2048.exe
```
Run the game:

```sh
2048.exe
```
## **3️⃣ Compile & Run (Linux)**
Open the terminal and navigate to the project folder.

Compile using GCC:
```sh
gcc 2048.c -o 2048
```
Run the game:
```sh
./2048
```
## ** 💡 Features**
✅ Classic 2048 gameplay in the console.
✅ Random tile generation for a fair challenge.
✅ Score tracking to monitor progress.
✅ Simple ASCII UI for easy interaction.
✅ Cross-platform support (Windows & Linux).

## **🔍 Example Gameplay Output**
```sh
------------------------------
    Welcome to 2048 Game!!!
    Reach 2048 to WIN :)
------------------------------
    Current Score : 0
------------------------------
        COMMANDS :
 n-> New game, w-> Up, s-> Down, d->Right, a->Left, q->QUIT

  .    .    .    .  
  .    2    .    .  
  .    .    .    .  
  .    .    .    .  

Enter command:
```
## 🚀 Contributing
Feel free to contribute by reporting issues or suggesting enhancements! You can:
🔹 Fork the repository
🔹 Create a new branch
🔹 Make your changes
🔹 Submit a pull request 🎉

## 📜 License
This project is open-source and available under the MIT License.

🔥 Enjoy playing 2048! If you like this project, give it a ⭐ on GitHub! 😊
