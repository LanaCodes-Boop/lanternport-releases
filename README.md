# Lanternport Repair Co.

A cozy first-person repair-shop game. You run a small repair shop in Lanternport, a harbour town on the
moon Sabal, and fix what people bring to your counter.

**This is an early test build (Milestone 2).** Every day townspeople bring broken gadgets to your hatch.
There are nine kinds of items and twelve hands-on repair jobs: foam and rinse, screws, diagnosing, board
swaps, soldering, wiring, glass, calibration, oil and polish, firmware, safe dials and batteries. In the
evening you buy upgrades and build onto the shop, and in the afternoon you can walk around Harbour
Square. The story beyond the first day is still to come.

You install it with the **Lanternport Launcher**. The launcher downloads the game and keeps it up to date
by itself: every time you open it, it checks for a new version and only downloads the parts that changed.

## Download

Go to **[Releases → Latest](../../releases/latest)** and download the file for your computer:

| Computer | File |
|---|---|
| Windows (64-bit) | `Lanternport-Launcher-Setup-<version>.exe` |
| Mac (Apple Silicon or Intel) | `Lanternport-Launcher-<version>-mac.zip` |

Ignore the other files on that page (`manifest.json`, `*.chunk`): that is game data the launcher fetches
itself.

The launcher and the game are not code-signed yet, so Windows and macOS will warn you the first time.
That is expected for this test build. Here is how to get past the warning.

## Windows

1. Run `Lanternport-Launcher-Setup-<version>.exe`.
2. If a blue box says **"Windows protected your PC"**: click **More info**, then **Run anyway**.
3. Follow the installer. It installs just for your user account and adds a **Lanternport Launcher**
   shortcut to the Start menu and the desktop.
4. Open the launcher and press **INSTALL** (this test build is about 120 MB). Then press **PLAY**.

To remove it later: in the launcher, *Settings → Uninstall…* removes the game (tick the box to also delete
your saves); then remove the launcher in Windows *Settings → Apps → Installed apps → Lanternport Launcher*.

## Mac

1. Double-click `Lanternport-Launcher-<version>-mac.zip` to unpack it.
2. Drag **Lanternport Launcher** into your **Applications** folder.
3. Open it. The first time, macOS blocks it because it is not from an identified developer. Then:
   open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to the
   message about Lanternport Launcher (you may need to confirm with your password).
   On older macOS versions you can instead right-click (or Control-click) the app, choose **Open**, and
   confirm.
4. Press **INSTALL** (this test build is about 180 MB). Then press **PLAY**.

To remove it later: in the launcher, *Settings → Uninstall…*; then drag the app from Applications to the
Bin.

## Updates

Nothing to do: open the launcher and it updates the game when a new version is out. You can pause a
download and continue later, even after closing the launcher. If something seems broken, *Settings →
Repair install* checks every file and downloads only what is damaged.

## If something goes wrong

Open the launcher's **Settings** and use **Game logs** or **Launcher logs** — they open the folders with the
log files. Send those files along with a short description of what happened.

| | Windows | Mac |
|---|---|---|
| Game logs | `%APPDATA%\Lanternport\logs` | `~/Library/Application Support/Lanternport/logs` |
| Launcher logs | `%APPDATA%\Lanternport Launcher\logs` | `~/Library/Logs/Lanternport Launcher` |

If the game shows no picture or crashes at start, try *Settings → Graphics renderer → Compatibility* in
the launcher and press PLAY again.

## Privacy

No account, no login, no telemetry. The launcher only connects to this GitHub page to check for and
download the game.
