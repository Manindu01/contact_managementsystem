# Contact Management System (C++)

A **simple console-based contact management application** implemented in C++ using a **doubly linked list**.  
This program allows users to add, view, search, edit, and delete contacts, as well as save and load them from a text file.

---

## 📖 Overview

The Contact Management System provides an easy way to manage a list of contacts directly through the console.  
It supports basic CRUD operations (Create, Read, Update, Delete) and stores all contacts in a local text file for persistence.

---

## ⚙️ Features

- ➕ Add new contacts (Name and Phone Number)
- 📋 Display all saved contacts
- 🔍 Search contacts by name or phone number
- ✏️ Edit existing contact details
- 🗑️ Delete a specific contact
- 🔄 Delete all contacts
- 💾 Save contacts to a text file (`contactbook.txt`)
- 📂 Load contacts automatically on startup

---

## 🧩 Files Included

| File Name | Description |
|------------|-------------|
| `ContactManegmentsystem.cpp` | Main C++ source code implementing the full program |
| `contactbook.txt` | Auto-generated file used to save and load contacts |

---

## 🛠 Requirements

- A C++ compiler (e.g., `g++`, `clang++`)
- Operating system: Windows / macOS / Linux
- Command Prompt or Terminal access

---

## 💻 How to Compile and Run

```bash
# Compile the program
g++ ContactManegmentsystem.cpp -o contactbook

# Run the program
./contactbook        # For Linux or macOS
contactbook.exe      # For Windows
🧠 How It Works

When the program starts, it asks for your name.

A main menu is displayed with options to add, search, edit, delete, or view contacts.

Contacts are stored in a doubly linked list structure in memory.

When you exit the program, all contacts are saved in contactbook.txt.

On the next run, the program automatically loads contacts from the file.
