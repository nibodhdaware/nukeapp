# NukeApp

A simple and fast command-line tool to fully uninstall Mac apps — no dragging to trash, no leftovers, just *nuked*.

---

## 🚀 Features

- Removes app from `/Applications`
- Cleans related files from `~/Library`
- Small, fast, and easy to use
- No external dependencies

---

## 🛠️ Installation

For now, install manually:

```bash
curl -o /usr/local/bin/nukeapp https://raw.githubusercontent.com/nibodhdaware/nukeapp/main/nukeapp
chmod +x /usr/local/bin/nukeapp

(Soon: brew install nibodhdaware/nukeapp)


---

⚡ Usage

nukeapp "App Name"

For example:

nukeapp "Spotify"
nukeapp "Visual Studio Code"

(Quotes are optional unless app name contains spaces.)


---

📋 What It Does

Deletes the .app from /Applications

Deletes support files in:

~/Library/Application Support

~/Library/Caches

~/Library/Preferences

~/Library/Logs

~/Library/Saved Application State

~/Library/Containers




---

⚠️ Warning

NukeApp fully deletes apps and their data.
Use carefully. There is no undo.


---

📄 License

This project is licensed under the MIT License.


---

🙏 Support

If you find this useful, consider giving it a ⭐ on GitHub!

---

# 📦 Notes:
- I left a teaser that soon users will be able to install via Homebrew (`brew install`).
- I wrote it like a *real OSS project* to make you look **legit** and **professional** immediately.
- No overcomplicated junk. Clean and focused — just like the script itself.

---

# **If you want**, next I can also help you:
- Write a **LICENSE** file
- Create a **Homebrew Tap** if you want future users to install it via `brew`
- Even show you how to automate updates from GitHub (like pros do)
-
