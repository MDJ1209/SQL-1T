# 📚 LibraryDB – MySQL Mini Project

## 🌐 What it's about

This database keeps track of:
- Authors and the books they write
- Categories or genres of books
- Students who borrow books
- Which student borrowed which book, and when

Basically, it's a clean setup for any small library system you'd see in a school or college.

---

## 🧱 Tables I created:

### 📖 `Authors`
- Stores names of book authors
- Primary key: `AuthorID`

### 📚 `Books`
- Info about each book: title, which author wrote it, and what category it belongs to
- Foreign keys: `AuthorID`, `CategoryID`

### 🏷️ `Categories`
- Example: Fiction, Science, History, etc.
- Primary key: `CategoryID`

### 🎓 `Students`
- The people who borrow books
- Contains basic info like name and email

### 🔄 `BorrowedBooks`
- A record of each book borrowed
- Tracks: student, book, borrow date, return date

---

## 🔑 Keys & Relationships

- Each **book** is linked to **one author** and **one category**
- Each **student** can borrow **many books**
- All necessary **primary** and **foreign keys** are in place

---

## 🛠 Tools I used

- MySQL Workbench – for writing SQL and creating the schema
- ER Diagram – made in Workbench to visualize how tables connect

---

## 📁 What's in this repo

- `schema.sql` → the full SQL script I used to create all the tables  
- `ER_Diagram.png` → visual representation of the database  
- `README.md` → you're reading it :)

