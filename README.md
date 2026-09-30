# PAYCORE Operations Console · Short Film Screen Props

An authentic, cinematic interactive screen prop built for short film production, simulating **PAYCORE** enterprise payment server infrastructure and live incident response across **Scene 4**, **Scene 5**, and **Scene 6**.

Designed with **predestined actor-driven typing**, authentic cybersecurity breach sequences, draggable terminals, and invisible hotkeys for camera takes.

---

## 🎬 Director & Actor Quick Cheat Sheet

All visible on-screen debug buttons are hidden to maintain 100% film realism. Use the keyboard shortcuts below to control scenes and takes seamlessly during filming.

### ⌨️ Global Keyboard Shortcuts

| Key / Shortcut | Function | Description |
| :--- | :--- | :--- |
| **`1`** | **Open Terminal 2** | Opens the floating audit terminal with predestined typing. |
| **`F4`** or **`Alt + 4`** | **Scene 4** | Normal Operations / Initial High Volume Warning. |
| **`F5`** or **`Alt + 5`** | **Scene 5** | Client sends malicious tool + download sequence. |
| **`F6`** or **`Alt + 6`** | **Scene 6** | System Meltdown / Failure / Cyber breach. |
| **`F7`** or **`Alt + 1`** / **`Alt + L`** | **Toggle Terminal 2** | Open or toggle the floating audit inspection terminal. |
| **`F8`** or **`Alt + M`** | **Instant Meltdown** | Manually force critical red meltdown state. |
| **`F9`** or **`Alt + R`** | **Reset Take** | Resets the current scene state for a fresh camera take. |
| **`Escape`** | **Dismiss / Close** | Closes Terminal 2 or dismisses active hacked popups. |

---

## 💻 Terminal 2 (Floating Audit Terminal) Guide

Jake opens Terminal 2 to inspect audit logs after the system halts.

### 1. Trigger
* Press **`1`** (or **`F7`** / **`Alt + 1`**).
* A floating Linux workstation terminal appears:
  ```text
  Last login: Today 22:10:04 on pts/2 from 192.168.1.104
  jake@workstation:~$ █
  ```
* **No auto-typing**: The cursor blinks and waits for the actor's physical keystrokes on camera.

### 2. Actor-Driven Predestined Typing
* Press **ANY keys** on the keyboard (letters, numbers, spacebar).
* Every key press types out the next character of the predestined command:
  ```bash
  cat /var/log/audit/execution.log
  ```
* The actor can type fast or slow to match their emotional pacing and camera framing.
* **`Backspace`**: Erases character by character for realistic pause/correction.
* **`Tab`**: Instantly autocompletes the remaining command.

### 3. Execution & Revelation
* Press **`Enter`**:
  * Output:
    ```text
    [OK] Connecting to local audit subsystem...
    [OK] Audit trail session: #AUD-2026-9014 (Read-Only)
    ```
  * Immediately renders the glowing red **`EXECUTION LOG`** card framing Jake:
    * **User:** `jake_admin`
    * **Remote IP:** `192.168.1.104 [Jake's IP]`
    * **Action:** Configuration update
    * **Status:** `Failed`
    * **Auth Key:** `Signed by jake_admin_privkey`
    * Subtext: *“May gumagamit ba ng account ko?” — What if I've been set up?*

### 4. Camera Framing Controls
* **Draggable Titlebar:** Click and drag the window header to position Terminal 2 anywhere on screen for optimal camera framing.
* **Window Buttons:** Functional macOS/Ubuntu style **[✕ Close]**, **[− Minimize]**, and **[□ Maximize]**.

---

## 📽️ Scene Breakdown & Flow

### 🎬 Scene 4 — Early Warning & Initial Triage
* **Visual:** Dark blue enterprise operations dashboard with degraded performance metrics (1,284 req/s).
* **Terminal:** Type any key into the bottom console to type `check-logs --target=PAYCORE-01` and press **Enter** to scan logs.
* **Chat:** Type any key in the chat composer to realistically type Jake's dialogue and press **Enter** to send. The Client automatically replies with realistic typing delays.

### 🎬 Scene 5 — The Malicious Maintenance Tool
* **Chat Attachment:** The client sends `maintenance_update.sh` requesting root/sudo privileges.
* **Interactive Flow:**
  1. Jake types: *"Is this already tested po?"*
  2. Client replies: *"Yes. All administrators use it. Just run it with administrator access."*
  3. The **Download** button pulses green. Clicking download (or typing in terminal) reveals the bottom-left download confirmation with a 3-second auto-close countdown.
  4. In the terminal, type any key to type: `sudo bash ./maintenance_update.sh` and press **Enter**.
  5. The sequence executes:
     * `MAINTENANCE IN PROGRESS…`
     * `Checking services…`
     * `Updating configuration…`
     * `Restarting payment service…`
     * `ERROR: Transaction queue unavailable`
  6. Pause for Jake's spoken line: *“Wait lang… bakit nag-error?”*
  7. Visual screen glitch, system turns **CRITICAL RED MELTDOWN**, streaming cyber breach errors, and hacked security alert popups appear.

### 🎬 Scene 6 — The Setup & Realization
* **Visual:** Red emergency alert banner, crashed service status, memory leak, dropped transactions.
* **Dialogue:** Jake messages the client about the error; client deflects and orders: *"There is no time for that. Just restore the system."*
* **The Climax:** Jake presses **`1`**, types in Terminal 2, presses **`Enter`**, and discovers the audit trail was executed from his own credentials and IP address.

---

## 🌐 GitHub Pages Deployment

To run this live on GitHub Pages:
1. Ensure `index.html` is present in the repository root.
2. Go to **Settings** → **Pages** in this GitHub repository.
3. Under **Branch**, select `main` (or `master`) and `/ (root)`.
4. Click **Save**. Within 1–2 minutes, your live prop will be accessible at:
   `https://<your-username>.github.io/props-maam-kim/`

---
*Created for short film production.*
