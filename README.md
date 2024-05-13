# Contact-app
# Application for taking users contacts, store and retrieve them for the user.

In this version, two new functions <h3>saveContacts</h3> and <h3>loadContacts</h3> are added. The saveContacts function serializes the contacts array into a JSON string and stores it in the local storage under the key '<h3>contacts</h3>'.
 The loadContacts function <h3>retrieves</h3> the contacts from the <h3>local storage</h3>, deserializes them, and <h3>updates</h3> the contacts array. These functions are called whenever a contact is added or deleted to ensure that the local storage stays up-to-date. Additionally, the loadContacts function is called when the page is loaded to load the contacts from local storage.