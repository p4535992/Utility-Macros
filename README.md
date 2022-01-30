# Utility Macros

This repo holds macros that I have found to be of general utility **and** have foud the time to push to GitHub so that others might make of them what they will.

This readme contains a summary of the functions and for at least some of them a followup section with any notes that I felt worth sharing about each one.

## Functions in this Repo

* **[Open Actor Sheets With...](Open-Actor-Sheets-With...)** fetchs a list of items from an actor allowing the user to pick one and then opens al of the actor's sheets that contain that item.

## Notes on Functions

### **Open Actor Sheets With...** 

This macro should be run with a token of interest selected.  The intent of the macro is to make it easier to chec or update all of the users of a given item.  Something I find both common and bothersome. 

It does the following:

1. Finds the types of items on that token (e.g. spell, weapon, etc.),
1. Provides a dialog soliciting the type of interest,
1. Finds all of the items of the specified type,
1. Provides a dialog soliciting a specific item of interest,
1. Opens the sheet of all the actors in the *Actors Directory*.

![Open_Actor_Sheets_With_Example.png](Images/Open_Actor_Sheets_With_Example.png)
