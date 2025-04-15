# 📝 Command Line Text Editor

A simple command-line based text editor built with Python, featuring basic file operations such as writing, displaying, deleting, and undo functionality using stack data structures.
This was done as an assignment to Data Structures Course, of making a basic application based project using data structure.

## 🚀 Features

- ✍️ Write text to a file
- 📄 Display contents of the file
- ❌ Delete last character (like a backspace)
- ↩️ Undo last action (write or delete)
- 💾 Auto-saving to `text.txt`

## 📂 File Structure

- `text.txt` – Stores the contents being edited
- `stack` class – Custom implementation to manage undo/redo using stacks

## 🛠 How It Works

The editor operates in a continuous loop offering the following options:

1. **Write** – Appends user input to `text.txt` and pushes characters to a stack  
2. **Display** – Prints the contents of the file  
3. **Delete** – Removes the last character from both the stack and the file  
4. **Undo** – Reverts the most recent action (write or delete)  
5. **Exit** – Quits the editor  

Stacks are used to manage text history:
- `s` stack tracks all characters written
- `dl` stack holds deleted characters for potential undo

## 🧠 Concepts Used

- Stack (LIFO) for undo/redo management
- File handling in Python (`open`, `read`, `write`, `append`)
- Basic control flow and input handling

# THANK YOU !!!
