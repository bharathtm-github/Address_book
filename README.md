# 📒 Address Book (C Project)

👤 Author: Bharath TM  
📅 Date: 06-11-2025  

---

📌 PROJECT DESCRIPTION

This project is a simple Address Book program written in C language.

It allows users to store and manage contact information using a menu-driven interface.

Each contact contains:

➤ Name  
➤ Phone Number  
➤ Email ID  

📂 All contacts are stored in a file called `contacts.csv`, so the data remains available even after the program is closed.

⚠ Dummy contacts are used only for testing.  
✔ Only user-added contacts are saved to the file.

---

🚀 FEATURES

➕ Create Contact  
✔ Add a new contact after validating all input details.

🔍 Search Contact  
Search contacts using:  
• Name  
• Phone Number  
• Email ID  

✏ Edit Contact  
✔ Modify contact details after the contact is found.

❌ Delete Contact  
✔ Remove an existing contact from the address book.

📋 List All Contacts  
✔ Display all contacts including dummy contacts.

💾 Save Contacts  
✔ Store new contacts permanently in the file.

🚪 Exit  
✔ Safely exit the program after saving data.

---

✅ VALIDATIONS IMPLEMENTED

👤 Name Validation  
✔ Only alphabets and spaces allowed  
❌ Numbers and special characters not allowed  
✔ Name cannot be empty

📱 Phone Number Validation  
✔ Must contain exactly 10 digits  
✔ Only numeric values allowed

📧 Email Validation  
✔ Must start with a lowercase letter  
✔ Must end with `@gmail.com`  
✔ Can contain alphabets, digits, and underscore (_)  
✔ Displays clear messages for valid or invalid input

---

⚙ FUNCTIONAL VALIDATIONS

➕ Create Contact  
✔ Checks all fields before saving  
✔ Prevents incomplete or invalid data

🔍 Search Contact  
✔ Search by name, phone, or email  
✔ Displays message if contact not found

✏ Edit Contact  
✔ Editing allowed only after contact is found  
✔ New values are validated again

❌ Delete Contact  
✔ Checks if contact exists before deletion  
✔ Removes contact without leaving empty entries

---

💻 COMPILATION AND EXECUTION

Compile the program:

gcc *.c

Run the program:

./a.out

---

📂 FILE HANDLING

The program uses a file named:

contacts.csv

✔ Only user-added contacts are stored in this file.

📄 File Format:

#<count>#
name,phone,email

📌 When the program starts, it loads contacts from this file.  
This ensures that previously saved contacts remain available.

---

🧠 CONCEPTS USED

✔ Structures – To store contact details  
✔ Functions – For modular programming  
✔ Header Files – For clean code organization  
✔ File Handling – To save and load contacts  
✔ Input Validation – To ensure correct data  
✔ String Handling – Using `strcmp()` and `strcpy()`  
✔ Menu-driven programming – For easy user interaction  

---

⭐ This project demonstrates fundamental C programming concepts and file handling techniques.
