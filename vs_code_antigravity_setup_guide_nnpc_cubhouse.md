# Building & Running **NNPC CubHouse** in VS Code with Google Antigravity

Whether you are using **Google Antigravity** (Google's agentic VS Code-based IDE) or standard **Visual Studio Code** with the Antigravity agent workflow, you can set up, preview, and expand **NNPC CubHouse** in minutes without needing Node.js or complex build tools.

---

## Step 1: Open Your Workspace Folder
1. Launch **Antigravity** (or **VS Code**).
2. Click **File → Open Folder...** (or press `Ctrl + K` then `Ctrl + O` on Windows/Linux, `Cmd + O` on Mac).
3. Create and select a new project folder named:
   ```text
   nnpc-cubhouse
   ```

---

## Step 2: Add `index.html` to Your Workspace
You can create the file manually or ask the Antigravity Agent to write it for you:

### Option A — Create Manually
1. In the left **Explorer** sidebar, click the **New File** icon and name it `index.html`.
2. Copy the complete code from your `index.html` artifact, paste it into `index.html`, and press `Ctrl + S` (`Cmd + S` on Mac).

### Option B — Use the Antigravity Agent Panel
1. Open the **Antigravity Agent / Chat** sidebar (`Ctrl + L` or `Cmd + L`).
2. Paste your `index.html` code or instruct the agent:
   > *"Create `index.html` in the root folder for NNPC CubHouse using our single-file HTML5, Tailwind CSS, and Vanilla JS architecture."*
3. Click **Accept** when the agent proposes creating `index.html`.

---

## Step 3: Launch & Preview in Browser
1. **Using Antigravity's Built-in Browser Preview:**
   - Ask the Antigravity Agent: *"Launch `index.html` in a local server and verify the preview."*
   - Antigravity will start a local HTTP server and open the live interactive preview directly inside its integrated browser pane so it can inspect and test changes automatically.
2. **Using the Live Server Extension (Manual Alternative):**
   - Open Extensions (`Ctrl + Shift + X` / `Cmd + Shift + X`), install **Live Server** by *Ritwick Dey*, right-click `index.html`, and choose **Open with Live Server**.

---

## Step 4: Iterating on NNPC CubHouse with Antigravity Prompts
Once your workspace is open, you can use Antigravity's **Planning** or **Fast** agent modes to add new features while keeping everything responsive:

- **Connect a Real Backend / Database:**
  > *"Refactor `localStorage` in `index.html` to sync member registrations, court bookings, and dues receipts with Supabase or Firebase Firestore while keeping an offline fallback."*
- **Add Automated Tournament Brackets:**
  > *"Add an 8-player and 16-player knockout tournament draw generator tab for NNPC CubHouse Kaduna."*
- **Add Custom Local Assets:**
  1. Create an `assets/` folder inside `nnpc-cubhouse` and drop in your official high-res club crest (`logo.png`) or court photos.
  2. Tell Antigravity: *"Replace the inline SVG crest in `index.html` with `./assets/logo.png` across the header and printable CR80 ID card."*

---

## Step 5: Deploying Online for Club Members
When you are ready to share **NNPC CubHouse** with members and visiting players in Kaduna:
1. Drag and drop your `nnpc-cubhouse` folder onto **Netlify Drop** (`app.netlify.com/drop`) or **Vercel**, or push it to a **GitHub** repository with **GitHub Pages** enabled.
2. Share the generated HTTPS URL with your members so they can book courts, register ratings, and print their ID cards from any phone or desktop.