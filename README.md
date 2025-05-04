# RevertCord Install Guide

This guide will help you revert Discord's layout using a custom CSS file and the [Vencord](https://vencord.dev) client mod.

## 📁 Step 1: Download the CSS File

1. Download the `RevertCord.css` file from this repository.
2. Or Copy the content buttom

> If you're hosting it yourself, upload it somewhere publicly accessible (like GitHub Pages, a CDN, or your own web server).

## 🔧 Step 2: Install Vencord

To use custom CSS in Discord, you need to install [Vencord](https://vencord.dev), a client mod for Discord.

### How to Install Vencord

1. Visit: [https://vencord.dev](https://vencord.dev)
2. Click **Install** and download the installer for your operating system.
3. Launch the installer and follow the instructions:
   - It will detect your Discord installation automatically.
   - Let it install the mod.

Once done, open Discord.

## 🎨 Step 3: Apply the Custom CSS

1. Open **Discord**.
2. Go to **User Settings** (⚙️ icon in the bottom left).
3. Scroll down and open the **Vencord** section.
4. Click on **Quick CSS**.
5. Paste the following line into the editor:

````css
/* STABLE VERSION */
@import url("https://raw.githubusercontent.com/HackVogel/RevertCord/refs/heads/main/RevertCord.css");
````

````css
/* BETA (EXPERIMENTAL) VERSION */
@import url("https://raw.githubusercontent.com/HackVogel/RevertCord/refs/heads/main/BetaCord.css");
````

## 🗣 SUPPORT
[Discord](https://discord.gg/purpur)
