# Ikidone: start here

One page: install it, connect your apps, make your first email report. About 10 minutes.

## What you need

- A Claude account on a paid plan (Pro, Max, Team or Enterprise).
- Your Slack account.
- Optional: Asana, Gmail, and Wispr Flow or Fathom for meeting notes.
- A Mac with Apple Silicon (M1 or newer) or a Windows PC.

## 1. Install

Open the [latest release](https://github.com/ibalbino/slack-tasks-releases/releases/latest) and
download the files for your computer into one folder.

**Mac:** the `.dmg`, `Install-Ikidone.command` and `How-to-install-Mac.txt`.

1. Open Terminal (Command + Space, type Terminal, press Enter).
2. Type `bash` and a space. Don't press Enter yet.
3. Drag `Install-Ikidone.command` into the Terminal window and press Enter.
4. Answer each question with `y` or `n`.
5. macOS will say Ikidone is from an unidentified developer. The installer opens the
   screen for it: in **System Settings > Privacy & Security**, click **Open Anyway**.

**Windows:** the `-setup.exe`, `Install-Slack-Tasks-Windows.bat`, `install-windows.ps1` and
`How-to-install-Windows.txt`.

1. Double-click `Install-Slack-Tasks-Windows.bat`.
2. Windows shows a blue window, "Windows protected your PC". Click **More info**, then
   **Run anyway**.
3. Answer each question with `y` or `n` and press Enter.

Why the warnings? The installers aren't signed with a paid Apple or Microsoft certificate yet.
The app's updates are signed, and the app refuses any update that isn't.

## 2. Set it up

Ikidone opens its setup window by itself.

1. **Claude:** sign in with your TFC Claude account.
2. **Slack:** click **Open Claude connectors**, connect Slack there, come back and click **Check**.
3. Click **Done**. The first list of tasks takes a minute or two.

Then, in **Settings > Connections**, connect what you use: Asana, Gmail, Wispr Flow, Fathom.
Each row shows whether the app is really connected, as which account, and when it was last
checked. If a row says **Needs attention**, click **Check**.

## 3. Use it

- The window lists the Slack messages waiting for you: Urgent, Soon, Later.
- Click a task to open it in Slack, draft a reply, snooze it or make it an Asana task.
- The circle marks it done. Drag a task by its grip to another group; **Undo** puts it back.
- The **?** button has a short guide for each tab.

## 4. Your first email report

1. **Settings > General > My team:** choose **Email**. The menu gets **Email report…**.
2. Open **Email report…** and click **Connect a client**.
3. In the client's Klaviyo: **Settings > Account > API keys > Create Private API Key**, with
   **Read-only** access for everything. Paste the key. It is kept in your computer's keychain.
4. Pick the client and the month, and click **Make the report**. It takes a few minutes.
5. The deck is saved to Downloads. **Open it in Google Slides** (upload it to Drive, then open
   it with Slides) so the fonts look right.
6. Before it goes to the client: check the orange `[check: …]` marks and the wording. Every
   number comes from Klaviyo; the marks are what Klaviyo couldn't give.

## When something goes wrong

- **The lists stopped changing:** look at the top of the window. If your Claude usage limit is
  used up, it says so and when it resets.
- **An app says Needs attention:** Settings > Connections > **Check**, or **Open Claude
  connectors** and connect it again.
- **You need help:** Settings > Updates & help. **Copy summary** puts a few lines on the
  clipboard to paste in Slack (no messages, names or client data). **Download** saves the full
  log if you're asked for it.
- **A list looks wrong:** Settings > Privacy & data > **Restore** brings back the lists of a day
  from the last week.

## Updates

Ikidone offers new versions by itself: click **Update** in its menu. After it restarts, a
box at the top says what changed.
