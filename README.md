---

# 🎮 How to Run **Lethal Company** on macOS (No Steam) via Crossover

This guide will help you run **Lethal Company** on **macOS** using [Crossover](https://www.codeweavers.com/crossover), **without using Steam**, using a pre-downloaded repack version.

---

## ✅ Requirements

* macOS 12 or later (Apple Silicon or Intel)
* [Crossover for macOS](https://www.codeweavers.com/crossover/download)
* Game build:
  `lethal.company.v72.build.18916695.incl.online-m4ckd0ge_repack (extract.me)`

---

## 📦 Step 1: Prepare the Game Files

1. **Download and Extract Zip File**

   * Get the file from the WhatsApp group link
   * Extract the `.zip` file
   * You should see:

     * `Setup.exe`
     * `m4ckd0ge.bin`

---

## 🍷 Step 2: Set Up a Crossover Bottle (SKIP ON WINDOWS)

1. **Open Crossover**

2. Click **"Bottle" → "New Bottle"**
<img width="465" height="220" alt="Screenshot 2025-08-08 at 11 39 01 AM" src="https://github.com/user-attachments/assets/683dd01f-7e9f-42a3-8d04-f1558a82f02b" />

3. Name your bottle (e.g., `LethalCompany`)

4. Choose:

   * **Windows 10 (64-bit)** as the environment

5. Wait for bottle creation to finish

---

## 🛠 Step 3: Install The Game

### Windows Only

1. If you are on Windows, you can proceed by executing the **"Setup.exe"** file and following the game installer prompts
2. Unzip `files_to_copy.zip`
3. Navigate to the game folder:

   ```
   C: -> Games -> Lethal Company (M4CKD0GE Repack)
   ```
4. Copy the contents of `files_to_copy` into the game folder


### A. Install Game into Bottle

1. In **Crossover**, select your `LethalCompany` bottle

2. Click **"Install Application into Bottle"**
<img width="288" height="249" alt="Screenshot 2025-08-08 at 11 40 39 AM" src="https://github.com/user-attachments/assets/d19a898e-2d20-419e-96ec-d6a6a0c4befe" />


3. Choose **"Install an unlisted application"**
<img width="873" height="255" alt="Screenshot 2025-08-08 at 11 41 48 AM" src="https://github.com/user-attachments/assets/bef116fa-3ff4-4264-af85-0c1d8b060ce3" />


4. Click **"Install"**

5. Select the extracted **`Setup.exe`** file

6. Follow the game installer prompts

---

### B. Add the Game Executable

1. In **Crossover**, select your `LethalCompany` bottle

2. Click **"Run Command..."**

3. Click **"Browse..."**, then navigate to the game's folder and select:

   ```
   Lethal Company.exe
   ```

4. *(Optional)* Enable ✅ **"Save Command as Launcher"** to make a shortcut

5. Click **"Run"**

---

### C. Enable `winhttp` in Wine (for Online Play)

1. With your bottle selected, open **Wine Configuration**

   * Right-click the bottle or click the gear icon → **"Wine Configuration"**
2. Go to the **"Libraries"** tab
3. Under **"New override for library"**, type:

   ```
   winhttp
   ```
4. Click **"Add"**
5. Make sure it appears as:

   ```
   winhttp (native, builtin)
   ```
6. If needed, click **"Edit"** and select **"native, builtin"**
7. Click **"Apply"**, then **"OK"**

---

### D. Paste Mod Files (for Online Play)

1. Unzip `files_to_copy.zip`
2. In Crossover, select the bottle → click **"Open C: Drive"**
3. Navigate to:

   ```
   Games -> Lethal Company (M4CKD0GE Repack)
   ```
4. Copy the contents of `files_to_copy` into the game folder
<img width="1220" height="603" alt="Screenshot 2025-08-08 at 12 06 23 PM" src="https://github.com/user-attachments/assets/e521bb9f-02c1-47ae-9e75-53b93df336dc" />


---

## 🎮 Step 4: Run the Game

* If you saved the launcher, click **Lethal Company** in Crossover to launch
* Otherwise, re-run the game using **"Run Command..."** (see Step 3B)

---

## 🧩 Tips & Notes

* **Performance**: Smooth on Apple Silicon with medium settings
* **Multiplayer**: Works if the repack supports networking features
* **Troubleshooting**:

  * If the game fails to launch, try switching to **Windows 7** mode in the bottle settings

---

> ⚠️ **Disclaimer**: This guide uses a repacked version of the game.
> Please ensure you **own the game legally**.
> This tutorial is provided **for educational purposes only**.

---

