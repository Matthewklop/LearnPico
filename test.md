# DragonPilot Installation Guide

This guide provides step-by-step instructions for installing DragonPilot (Release 2) on your EON/C2 device.

## Basic Usage

### Step 1: Connect to Wi-Fi
📶 Connect your device to Wi-Fi as you normally would.

### Step 2: Get the IP Address
1. 📱 Navigate to your device settings.
2. ⚙️ Go to "More Options."
3. ⋮ Tap the triple-dot icon in the upper right corner and select "Advanced."
4. 🔍 Scroll down and note the IPv4 address, which will look something like `192.168.0.xxx`.

### Step 3: Download the NEOS Default/Setup SSH Key
💾 Download and save the NEOS default/setup SSH key to your machine as `id_rsa`.

> **Note:** This is different from any GitHub SSH key you may have.

### Step 4: Connect to Your EON/C2
🔐 Use the saved SSH key to connect to your EON/C2.

Open a terminal and run the following command, replacing `[pathname of saved id_rsa]` with the path to your downloaded key and `[your-c2-ip-address]` with the IP address noted earlier:

```bash
ssh -i [pathname of saved id_rsa] comma@[your-c2-ip-address]
