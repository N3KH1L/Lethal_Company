
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
<img width="465" height="220" alt="Screenshot 2025-08-08 at 11 39 01 AM" src="https://github.com/user-attachments/assets/683dd01f-7e9f-42a3-8d04-f1558a82f02b" />

3. Name the bottle (e.g., `LethalCompany`)
4. Choose:
   - **Windows 10 (64-bit)** as the environment
   - Wait for bottle creation to finish

---

## 🛠 Step 3: Install The Game

### 🛠 A. Install Game Into Bottle

In the **LethalCompany** bottle:
1. Go to the bottle → **Install Application into Bottle**
<img width="288" height="249" alt="Screenshot 2025-08-08 at 11 40 39 AM" src="https://github.com/user-attachments/assets/d19a898e-2d20-419e-96ec-d6a6a0c4befe" />

2. Click on **Install an unlisted application**
<img width="873" height="255" alt="Screenshot 2025-08-08 at 11 41 48 AM" src="https://github.com/user-attachments/assets/bef116fa-3ff4-4264-af85-0c1d8b060ce3" />

3. Click **Install**
   - It should now ask you for an installer file

4. Select the **Setup.exe** file that you have extracted from the zip and click **Choose installer**

5. A game installer window should open
   - Follow the instructions in the window and wait for installation

---

### 🧭 B. Add the Game Executable

1. **Open Crossover**
2. **Select Your Bottle**
   - In the sidebar, select the bottle you created earlier (e.g., `LethalCompany`).
3. **Click "Run Command..."**
   - This opens a window to run a custom `.exe` file.

4. **Browse for the Game File**
   - Click **"Browse..."** and navigate to the Games folder (or the folder you installed the game in).
   - Select the game's executable file:
     ```
     Lethal Company.exe
     ```

5. **(Optional) Save as Launcher**
   - Enable ✅ **"Save Command as Launcher"** to create a shortcut in Crossover.

6. **Click "Run"**
   - The game should now launch inside the bottle.

---

### ⚙️ C. Enable WinHTTP in Wine (Required for Online Play)

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

### 📁 D. Paste Mod Folders (Required for Online Play)

1. Unzip the **files_to_copy.zip** file

2. Navigate to the bottle and click on **Open C: Drive**
   - This should open a new window with the bottle files

3. Navigate to the game folder (usually located in **/Games/Lethal Company (M4CKD0GE Repack)/**)

4. Copy the contents of the extracted **files_to_copy.zip** file into the game folder

<img width="1220" height="603" alt="Screenshot 2025-08-08 at 12 06 23 PM" src="https://github.com/user-attachments/assets/e521bb9f-02c1-47ae-9e75-53b93df336dc" />

---
## 🎮 Step 4: Run the Game

- If you haved saved the command as a launcher, you should see Lethal Company in the bottle
   - Click on it to start the game
- Otherwise, you can start the game by following the instructions in Step 3B

---

## 🧩 Tips & Notes

- **Performance**: On Apple Silicon, performance is generally good with medium settings.
- **Multiplayer**: Online co-op may work if the repack supports it and required networking features are intact.
- **Fixes**: If the game fails to launch, try running it in **Windows 7 mode** or adjusting bottle settings.

---



> ⚠️ *This method uses a repacked version of the game. Please ensure you own the game legally. This guide is for educational purposes only.*
