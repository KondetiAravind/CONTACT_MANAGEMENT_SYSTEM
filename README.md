# 📇 Contacts Management System (C Language)

This is a simple **Contacts Management System** written in the **C programming language**. It is a terminal-based application that allows users to manage contacts by adding, viewing, editing, deleting, and searching entries. ANSI escape codes are used to enhance the terminal interface with colored output.

---

## 📌 Features

- ➕ Add new contacts (Name, Phone, Email)
- 📋 View all saved contacts
- 🗑 Delete a contact by name
- 📝 Edit contact details
- 🔍 Search for a contact by name or phone number
- 🎨 Colorful UI with ANSI escape sequences
- 🧠 Basic input validation for phone number length

---

## 📁 Project Structure

```
.
├── contact_manager.c     # Main source code
├── README.md             # Project documentation
```

---

## 🚀 Getting Started

### 📥 Prerequisites

- A C compiler (e.g., GCC)
- Works on Linux, Windows (with terminal), or macOS

### ⚙️ Compilation

```bash
gcc contact_manager.c -o contact_manager
```

### ▶️ Run the Program

```bash
./contact_manager
```

---

## 💻 Sample Output

```text
1.Add Contact
2.View Contacts
3.Delete Contact
4.Edit Contact
5.Find Contact
6.Exit

Enter your choice: 1
Enter name: Aravind
Enter phone number: 9876543210
Enter email: aravind@example.com

Contact added successfully!
```

---

## 📚 Concepts Demonstrated

- Use of `struct` in C
- Arrays of structures
- ANSI color codes for terminal text
- Input handling and basic validation
- Modular function design (`add`, `view`, `edit`, `delete`, `find`)

---

## 🛠 Future Improvements

- [ ] File-based persistence (save/load contacts)
- [ ] Better validation (e.g., email format)
- [ ] Search/filter multiple results
- [ ] GUI version using C/C++ or Python

---

## 👨‍💻 Author

**Kondeti Aravind**   
School of Electrical and Computer Sciences (SECS), IIT Bhubaneswar  
📧 22cs02008@iitbbs.ac.in  
🔗 [GitHub Profile](https://github.com/kondetiaravind)
