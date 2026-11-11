# Week 1 — Linux basics lab

## 📋 Overview
This write-up documents the 2-hour deep lab completed entirely from memory. The objective was to reinforce core Linux navigation, file management, and log analysis skills without using external notes.

## 🚀 Lab Steps Executed

### 1. Directory Navigation (20 Directories Explored)
I traversed the Linux filesystem hierarchy using `cd` and verified paths with `pwd`. Key system areas inspected included:
- Root and configurations: `/`, `/etc`, `/etc/ssh`, `/etc/default`
- System logs and variables: `/var`, `/var/log`, `/var/cache`, `/var/backups`
- Binary and system files: `/bin`, `/usr`, `/usr/bin`, `/tmp`
- User space: `/home`, `~`, `~/Documents`, `~/Downloads`

### 2. File and Folder Structure Operations
I built and manipulated a directory structure in the home user space to practice file operations:
- **Creation:** Formed a nested directory tree using `mkdir -p lab_challenge/level1/level2` and generated blank files with `touch`.
- **Replication:** Copied files across directories utilizing `cp`.
- **Displacement:** Moved and renamed testing files with `mv`.
- **Removal:** Cleaned up the testing environment using `rm` for files and `rm -r` for recursive directory deletion.

### 3. System Log Analysis
I analyzed critical system logs using privileged commands (`sudo`) combined with `less` and `tail` to monitor live system behavior:
- `/var/log/syslog`: Inspected global system messages and background daemon activities.
- `/var/log/auth.log`: Reviewed authentication logs, tracking successful/failed login attempts and `sudo` executions.

## 🧠 Key Takeaways
- Using `mkdir -p` is highly efficient for instantly deploying multi-level testing directory baselines.
- Appending `-n` to `tail` helps isolate specific recent anomalies in high-volume log streams like `syslog`.
- Operating strictly from memory dramatically increases command-line fluency and muscle memory for real-world operations.
