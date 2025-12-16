# 🕵️ Day 2: Investigating with Grep & Pipes

Today I learned how to filter through data to find specific information, a critical skill for log analysis in cybersecurity.

## 1. The Grep Command
`grep` stands for "Global Regular Expression Print". It searches for a specific pattern of text within a file.

### Commands Executed:
- **`grep "hacker" server_logs.txt`**:
  - searched inside my log file and printed only the line containing the suspicious user "hacker".
  - This is useful for quickly spotting intrusions in massive log files.

## 2. Piping (|)
I learned that the pipe symbol `|` allows me to chain commands together.
- **`history | grep "git"`**:
  - I took the output of my entire command history and "piped" it into grep to filter for Git commands only.

## 📸 Proof of Work
- [View Grep Analysis](./grep-practice.png)
