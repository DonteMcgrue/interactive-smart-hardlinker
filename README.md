# 🗂️ interactive-smart-hardlinker - Easy Hardlink Creation & File Management

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](https://github.com/DonteMcgrue/interactive-smart-hardlinker/releases)

## 📋 What is interactive-smart-hardlinker?

interactive-smart-hardlinker is a simple tool that helps you create hardlinks for your files using a step-by-step approach. It lets you explore your folders one level at a time and automatically skips files that are already linked elsewhere. This keeps your storage tidy and avoids duplicate copies. You can also choose to save logs that show what changes the tool made.

This program runs on Linux systems and uses a command line interface (CLI). It is designed to make managing files easier without needing deep technical skills.

## 💻 System Requirements

Before you start, make sure your computer meets these basic needs:

- Operating System: Linux (Ubuntu, Debian, Fedora, or any Linux with bash)
- Shell: Bash (version 4 or higher recommended)
- Disk Space: Enough free space for your files and hardlink storage
- User Permissions: You need permission to read, write, and create files in the folders you want to organize
- Terminal: Any terminal or command prompt available on your Linux system

You do not need programming knowledge to use this tool. A basic understanding of launching commands in a terminal helps but is not required.

## 🚀 Getting Started

Follow these steps to start using interactive-smart-hardlinker.

### 1. Download the tool

Click the button below to go to the release page where you can download the tool:

[![Download Latest Release](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](https://github.com/DonteMcgrue/interactive-smart-hardlinker/releases)

On the releases page, look for the latest version and download the file marked for Linux systems. The filename usually ends with `.sh` or similar.

### 2. Save the file

Once downloaded, move the file to a folder where you keep your scripts or tools. For example, you can create a folder called `~/tools` in your home directory.

### 3. Make the script executable

Open your terminal, navigate to the folder where you saved the file, and make it executable. You can do this by typing:

```bash
chmod +x interactive-smart-hardlinker.sh
```

Replace `interactive-smart-hardlinker.sh` with the actual name of the file you downloaded.

### 4. Run the script

Start the tool by typing in the terminal:

```bash
./interactive-smart-hardlinker.sh
```

If you get a "permission denied" error, double-check that you used the `chmod` command above.

### 5. Follow the on-screen prompts

The program will guide you through selecting directories and files. You will see options to browse your folder tree level by level. Just enter the number or name shown to move into that folder or select files.

The tool will check if files already have hardlinks by looking at their inodes (a kind of file ID). It will skip files if it finds duplicates. You can choose to save a detailed log at the end that reports which files were linked or skipped.

## 🛠️ How to Use interactive-smart-hardlinker

Here are the main features and how you can use them:

- **Hierarchical Navigation**  
  You can move through folders step-by-step rather than all at once. This helps you focus on one part of your file system at a time.

- **Smart Duplicate Detection**  
  Instead of scanning for duplicates by name or size, the script uses the inode number. This means it correctly identifies files already linked somewhere else on your disk.

- **Logging**  
  If you like, you can save a log file that records what the script did. This can help with backups or audits later.

### Typical workflow

1. Launch the script.
2. Choose the top folder to start.
3. Browse into subfolders.
4. Select files or directories to hardlink.
5. Review the list of files to process.
6. Confirm the operation.
7. View or save the log file.

## 🔧 Common Commands Overview

- Use arrow keys or type numbers to navigate menus.
- Enter `b` to go back to the previous folder.
- Enter `q` at any time to quit the script safely.
- Confirm actions with `y` for yes and `n` for no.

## ⚠️ Tips and Best Practices

- Always run the script on a backup or test folder first until you understand the behavior.
- Make sure you have the necessary permissions for the folders you manage.
- Avoid running the script on system folders or folders with active programs.
- Use the logging feature to keep records of your file changes.
- Do not delete files that the script has hardlinked without checking your backups.

## 📥 Download & Install

Visit the release page to download the latest version:

[Download interactive-smart-hardlinker](https://github.com/DonteMcgrue/interactive-smart-hardlinker/releases)

Choose the Linux-compatible file (.sh script) and save it on your computer.

After download:

1. Open your terminal.
2. Navigate to where you saved the script.
3. Run the following command to allow execution:

```bash
chmod +x interactive-smart-hardlinker.sh
```

4. Start the tool with:

```bash
./interactive-smart-hardlinker.sh
```

If you are new to using terminal commands, many Linux distributions provide guides on opening a terminal and changing permissions.

## 🧩 Features at a Glance

- Interactive browsing of directories  
- Level-by-level folder navigation  
- Hardlink creation with inode checks  
- Automatic skip of already hardlinked files  
- Optional detailed logging of operations  
- Simple bash script with no extra dependencies  
- Designed for file management and deduplication  
- Works well on media servers or backup setups  

## 🛡️ Security and Privacy

This tool runs locally on your machine and does not send data over the internet. Your files stay on your computer throughout the process. Always download the script from the official release page to ensure safety.

## 🚑 Troubleshooting

- **“Permission denied” errors:**  
  Run `chmod +x` to make the script executable. Also, ensure you have read/write permissions for your folders.

- **Script does not start:**  
  Check you are running the script from the correct folder with `./` prefix.

- **Unexpected errors:**  
  Close the script and restart your terminal. Try running on a different folder. Check logs if available.

- **Log file missing:**  
  Ensure you selected the option to save logs during the script run.

## 📚 Additional Resources

For more help, visit the official GitHub page:

https://github.com/DonteMcgrue/interactive-smart-hardlinker

You can find updates, report issues, or ask questions there.

## 🔖 Topics

This tool fits many uses including automation, backup, file organization, and efficient storage management on Linux systems.

Tags include: automation, backup, bash, cli, deduplication, file-management, file-organizer, hardlink, hardlinking, hardlinks, interactive, linux, media-server

---

This covers everything a non-technical user needs to download, set up, and start using the interactive-smart-hardlinker tool.