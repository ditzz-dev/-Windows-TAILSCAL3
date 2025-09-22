<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=slice&color=gradient&height=250&section=header&text=Windows%2011%20Ultimate%20RDP&fontSize=60&fontAlignY=40" />
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Version-v7.3-blue?style=for-the-badge">
    <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
    <img src="https://github.com/ditzz-dev/Windows-11-Ultimate-RDP/actions/workflows/main.yml/badge.svg">
</p>

This isn't just a script; it's a fully automated platform for deploying a high-performance, customizable Windows 11 RDP session directly from GitHub Actions, secured via Tailscale.

---

## 🔥 The Ultimate Leap: From v4 to v7

This version represents a quantum leap from its predecessors. We've moved from a rigid script to a dynamic, user-controlled platform.

| Feature             | Old Era (v4 & Below)               | ✨ **The Ultimate Era (v7)** ✨          |
| :------------------ | :--------------------------------- | :--------------------------------------- |
| **Connectivity**    | Ngrok (Public, less stable)        | **Tailscale** (Secure, private P2P)      |
| **Customization**   | Static (Required code edits)       | **Fully Dynamic** (Choose theme, apps, wallpaper via UI) |
| **Software**        | Bare OS                            | **Automated Installation** (Steam, OBS, Chrome, etc.) |
| **User Experience** | Plain text logs                    | **Rich UI** (Colored logs & a clean Summary page) |
| **Performance**     | Standard OS                        | **Performance-Tuned** (Debloated, optimized power plan) |

---

## ✨ Core Features

-   🚀 **Instant Deployment**: Get a powerful Windows environment running in minutes.
-   🔒 **Secure & Stable Connectivity**: Powered by Tailscale for a private, peer-to-peer connection. No public IPs, no open ports.
-   🎨 **Deep Customization**: Use the `workflow_dispatch` menu to choose your theme, install optional apps, and set a custom wallpaper from any URL.
-   ⚡ **Performance-Tuned**: Automatically debloats Windows, activates the "Ultimate Performance" power plan, and disables mouse acceleration for maximum responsiveness.
-   🕵️ **Stealth Mode**: System information is spoofed to help bypass common VM detection mechanisms.

---

## 🚀 Quick Start Guide

Follow these steps to deploy your own Ultimate RDP session.

### 1. Fork the Repository
Click the **Fork** button at the top-right of this page to create your own copy.

### 2. Get Your Tailscale Auth Key
-   Navigate to your [Tailscale Admin Console > Auth Keys](https://login.tailscale.com/admin/settings/keys).
-   Click **Generate auth key...**
-   Make the key `Reusable` and `Ephemeral`.
-   **Copy the generated key**. You will only see it once!

### 3. Create a GitHub Secret
-   In your forked repository, go to **Settings > Secrets and variables > Actions**.
-   Click **New repository secret**.
-   Name the secret **`TAILSCALE_AUTH_KEY`**.
-   Paste your Tailscale auth key into the `Secret` field.

### 4. Run the Workflow
-   Go to the **Actions** tab in your repository.
-   Select **Windows 11 Ultimate RDP** from the sidebar and click **Run workflow**.
-   **This is your command center:**
    -   Choose your preferred theme.
    -   Decide whether to install extra applications.
    -   Optionally, paste an image URL for your wallpaper.
-   Click the green **Run workflow** button.

### 5. Connect via RDP
-   Wait for the workflow to complete the setup steps (usually 3-5 minutes).
-   Go to the **Summary** page of the running workflow.
-   All your access details (Tailscale IP, Usernames, Passwords) will be displayed there, ready to use.

---

## ⚠️ Important Disclaimer

This is an **ephemeral environment**. The virtual machine and all its data will be **permanently destroyed** when the workflow is canceled or finishes its 6-hour runtime.

**DO NOT STORE ANY CRITICAL OR SENSITIVE DATA IN THE SESSION.**

This project is for educational and experimental purposes. Please use GitHub's resources responsibly and in accordance with their terms of service.
