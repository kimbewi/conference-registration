# Run the website (one step)

Everything is already installed in this folder. You do **not** need Node.js on your Mac.

## Option A — Desktop shortcut

Double-click **`Conference Portal`** on your **Desktop**.

## Option B — Double-click in this folder

Double-click **`Start Website.command`** in Finder.

If macOS blocks it: right-click → **Open** → **Open** again.

## Option C — Terminal

```bash
/Users/shu/conference-registration/start.sh
```

---

The first time may take 2–5 minutes (downloads Node + packages). After that it starts in seconds.

Browser opens: **http://localhost:3000**

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@conference.local | admin12345 |
| User | participant@conference.local | user12345 |

Press **Ctrl+C** in Terminal to stop.

---

## Push to GitHub (one time)

```bash
cd /Users/shu/conference-registration
chmod +x push-to-github.sh
./push-to-github.sh
```

Sign in when the browser opens. Your repo will be created as `conference-registration` on your GitHub account.
