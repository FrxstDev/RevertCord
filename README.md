# RevertCord Install Guide

This guide will help you revert Discord's layout using a custom CSS file and the [Vencord](https://vencord.dev) client mod.

---

## 📁 Step 1: Download the Required Files

You need two files:

1. [`RevertCord.css`](#) — The main style sheet to revert Discord's layout.
2. [`settings.json`](#) — Pre-configured Vencord settings for optimal experience.

### 🔽 What to Do:

* Download both files from this repository.
* Alternatively, copy the CSS content manually (see below).
* Place the `settings.json` file into the following folder on your computer:

```
%appdata%\Vencord\settings
```

> 💡 To open that path, press `Win + R`, paste it in, and press Enter.

---

## 🔧 Step 2: Install Vencord

To use custom CSS in Discord, you need to install [Vencord](https://vencord.dev), a client mod for Discord.

### How to Install Vencord

1. Go to [https://vencord.dev](https://vencord.dev)
2. Click **Install** and download the installer for your operating system.
3. Run the installer and follow the steps:

   * It will detect your Discord installation automatically.
   * Let it install the mod.
4. Once installed, launch Discord.

---

## 🎨 Step 3: Apply the Custom CSS

1. Open **Discord**.
2. Go to **User Settings** (⚙️ icon in the bottom left).
3. Scroll down to the **Vencord** section.
4. Click on **Quick CSS**.
5. Paste one of the following import lines into the editor:

```css
/* STABLE VERSION */
@import url("https://raw.githubusercontent.com/HackVogel/RevertCord/refs/heads/main/RevertCord.css");
```

```css
/* BETA (EXPERIMENTAL) VERSION */
@import url("https://raw.githubusercontent.com/HackVogel/RevertCord/refs/heads/main/BetaCord.css");
```

```css
/* BETA (EXPERIMENTAL) WITH DISABLED CUSTOM USER PROFILE COLORS */
@import url("https://raw.githubusercontent.com/HackVogel/RevertCord/refs/heads/main/RevertCord-without-profile-colors.css");
```

> 💾 Don't forget to **Save** after pasting the code!

---

## 🗂 Optional: Customize Further

Once `settings.json` is placed in the correct folder, your Vencord will be pre-configured with the best settings for RevertCord. You can still tweak things inside Discord at any time.

---

## 🗣 Support

Need help or want to chat?

Join us on **[Discord](https://discord.gg/purpur)**
