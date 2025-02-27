# Bore Setup Guide

## Windows

### Step 1: Download Bore
1. Go to the Bore releases page: https://github.com/ekzhang/bore/releases/latest
2. Download the correct file for Windows (`bore-vx.x.x-x86_64-pc-windows-msvc.zip`).
3. Extract the `bore.exe` file to **any folder** you prefer.

### Step 2: Download the Batch File
1. Download https://github.com/maskersss/bore-setup/releases/download/1.0.0/bore.bat.
2. Save it into **the same folder** where `bore.exe` is located.

> [!IMPORTANT]
> Make sure `bore.bat` is in the **same folder** as `bore.exe`!

### Step 3: Run Bore
1. Double-click `bore.bat`.
2. A terminal window should open, running Bore.
3. You should see `listening at bore.pub:xxxxx` at the end of last line, the `bore.pub:xxxxx` is the IP address you should give to the other person if you're playing Minecraft together.

---

## Linux & macOS (Advanced Users)

### Step 1: Download Bore
1. Go to the Bore releases page: https://github.com/ekzhang/bore/releases/latest
2. Download the correct file:
   - **Linux:** `bore-vx.x.x-x86_64-unknown-linux-musl.tar.gz`
   - **macOS (M-series Mac):** `bore-vx.x.x-aarch64-apple-darwin.tar.gz`
   - **macOS (Intel Mac):** `bore-vx.x.x-x86_64-apple-darwin.tar.gz`
3. Extract the archive and place `bore` in any folder.

### Step 2: Download the Shell Script
1. Download https://github.com/maskersss/bore-setup/releases/download/1.0.0/bore.sh.
2. Save it in **the same folder** as `bore`.

> [!IMPORTANT]
> Make sure `bore.sh` is in the **same folder** as `bore`!

### Step 3: Make it Executable
```sh
chmod +x bore.sh
```

### Step 4: Run Bore
```sh
./bore.sh
```

That's it! You should see `listening at bore.pub:xxxxx` at the end of last line, the `bore.pub:xxxxx` is the IP address you should give to the other person if you're playing Minecraft together.
