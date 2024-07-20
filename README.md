Contact Manager GUI Program


Overview

This program allows users to store and manage contact information using a graphical user interface (GUI). 
It provides options to add new contacts, view the contact list, edit existing contacts, and delete contacts. The program stores contacts in memory for persistent storage.


Features:


1.Add Contact:

  Enter name, phone number, and email address to add a new contact
  Validate user input to ensure correct format
   Display a success message when the contact is added

2.View Contacts:

  Display a list of all contacts in the system
    Show contact name, phone number, and email address
    Allow users to select a contact to edit or delete

3.Edit Contact

  Select a contact to edit from the list
    Update name, phone number, and email address as needed
    Display a success message when the contact is updated

4.Delete Contact

  Select a contact to delete from the list
    Confirm deletion to prevent accidental removal
    Display a success message when the contact is deleted

Technical Details:


Storage

  Contacts are stored in memory for persistent storage
    Data is saved to a file when the program exits
    Data is loaded from the file when the program starts

User Interface

  Graphical user interface (GUI) built using Tkinter library
    Easy-to-use interface with buttons, labels, and text fields



How to Use:

   Run the program by executing the Python script
    Click the "Add Contact" button to add a new contact
    Enter contact information in the provided fields
    Click the "View Contacts" button to display the contact list
    Select a contact to edit or delete from the list
    Click the "Edit Contact" button to update a contact
    Click the "Delete Contact" button to remove a contact


