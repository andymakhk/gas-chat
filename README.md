gas-chat
========

google appscript chat with google spreadsheet

from: https://code.google.com/p/app-chat/



App Chat: Apps Scripts (Server-side)

So, this folder is basically a copy of the two Google Apps Script scripts
have running on two spreadsheets.

********************************************************************************
* Spreadsheet name:  App Chat (fcpsschools.net): Form                          *
* Spreadsheet id:    t_fqbMsrUaU99H0BBefCKYg                                   *
* Project name:      App Chat (fcpsschools.net): Form                          *
* Project key:       MQMncnBO5ldlVGWZJ7BwXFTnbm4_TkrO4                         *
* Filename(s):       AddToSpreadsheet.js                                       *
********************************************************************************

This script file handles everything that needs to happen when the form that 
adds the user to the system is submitted, and all necessary helper functions. 
This includes the trigger that runs when the spreadsheet that is generated for 
the user is edited, and a function to clean up references to that trigger that 
still exist after the user-specific spreadsheet has been deleted.

********************************************************************************
* Spreadsheet name:  App Chat (fcpsschools.net): Main                          *
* Spreadsheet id:    tS9UIr5fIO6cnk_cSiu-RcA                                   *
* Project name:      App Chat (fcpsschools.net): Main                          *
* Project key:       MJxWxSTKpcPmGkPF2Xb85eTnbm4_TkrO4                         *
* Filename(s):       Main.js                                                   *
********************************************************************************

This is the main spreadsheet where everything goes. The chat logs and user 
list, yay. Functions from the other page also open this spreadsheet, and only 
I and any moderators can edit it via edit permissions set on the folder. Its 
scripts manage tasks that need to be done repeatedly, like updating people's 
statuses to idle and admin functions like deleting users.
