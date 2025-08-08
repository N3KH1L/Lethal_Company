
# Instructions to play Lethal Company


# 🎮 Run Lethal Company on macOS (No Steam) via Crossover

This guide helps you run **Lethal Company** on **macOS** using [Crossover](https://www.codeweavers.com/crossover), without using Steam. Instead, we use a pre-downloaded repack version of the game.

---

## ✅ Requirements

- macOS 12 or later (Apple Silicon or Intel)
- [Crossover for macOS](https://www.codeweavers.com/crossover/download)
- Game build: `lethal.company.v72.build.18916695.incl.online-m4ckd0ge_repack (extract.me)`  

---

## 📦 Step 1: Prepare the Game Files

1. **Download and Extract Zip File**
   - Download the zip file from the link in the Whatsapp group
   - Extract the zip file
   - You should have a folder that has a **Setup.exe** and a **m4ckd0ge.bin** file

---

## 🍷 Step 2: Set Up a Crossover Bottle

1. **Open Crossover**
2. Click **"Bottle" > "New Bottle"**
<img width="472" height="242" alt="Screenshot 2025-08-08 at 11 36 34 AM" src="https://github.com/user-attachments/assets/35cca4eb-82be-4601-8c41-64585e70fae0" />
4. Name the bottle (e.g., `LethalCompany`)
5. Choose:
   - **Windows 10 (64-bit)** as the environment
   - Wait for bottle creation to finish

---

## 🛠 Step 3: Install The Game
   ## 🎮  Add and Configure the Game in the Bottle

Once you've extracted the game files and created a new bottle in Crossover, follow these steps to run the game and enable networking.



### 🧭 A. Add the Game Executable

1. **Open Crossover**
   - Launch the Crossover app.

2. **Select Your Bottle**
   - In the sidebar, select the bottle you created earlier (e.g., `LethalCompany`).

3. **Click "Run Command..."**
   - This opens a window to run a custom `.exe` file.

4. **Browse for the Game File**
   - Click **"Browse..."** and navigate to the extracted folder.
   - Select the game's executable file:
     ```
     Lethal Company.exe
     ```

5. **(Optional) Save as Launcher**
   - Enable ✅ **"Save Command as Launcher"** to create a shortcut in Crossover.

6. **Click "Run"**
   - The game should now launch inside the bottle.

---

### ⚙️ B. Enable WinHTTP in Wine (Required for Online Play)

To ensure online/multiplayer functionality works correctly, you must manually enable the `winhttp` library in the bottle's Wine settings.

Follow these steps:

1. **Open Wine Configuration**
   - With your `LethalCompany` bottle selected, click the gear icon or right-click → **"Wine Configuration"**

2. **Go to the "Libraries" Tab**
   - In the Wine Configuration window, switch to the **Libraries** tab.

3. **Add `winhttp`**
   - Under **"New override for library"**, type:
     ```
     winhttp
     ```
   - Click **"Add"**

4. **Confirm Override**
   - You should now see:
     ```
     winhttp (native, builtin)
     ```
   - If not, select it in the list and choose **"Edit"** to set it manually to **native, builtin**

5. **Click "Apply"**, then **"OK"**

---

> 🧠 Tip: If the game doesn’t launch or shows network-related errors, enabling `winhttp` typically resolves it. You can return to this setting any time via Wine Configuration.

---

## 🎮 Step 4: Run the Game

1. In Crossover, click the **"Run Command"** button inside your bottle
2. Click **"Browse..."**, and select the game’s `.exe` (e.g., `Lethal Company.exe`) from the extracted folder
3. (Optional) Check **"Save Command as Launcher"** to create a shortcut for future use
4. Click **"Run"**

---

## 🧩 Tips & Notes

- **Performance**: On Apple Silicon, performance is generally good with medium settings.
- **Multiplayer**: Online co-op may work if the repack supports it and required networking features are intact.
- **Fixes**: If the game fails to launch, try running it in **Windows 7 mode** or adjusting bottle settings.

---



> ⚠️ *This method uses a repacked version of the game. Please ensure you own the game legally. This guide is for educational purposes only.*
