## License
This project is licensed under the PolyForm Noncommercial License 1.0.0.  
You may use, modify, and share this code for noncommercial purposes only.  
See the LICENSE file for details.

- You can support my work through Patreon at https://www.patreon.com/c/CloudZero

# IMPORTANT NOTE:
- Because I don't have the money to pay for a publisher certificate, there will be popups warning you about the files, some may ask you to send the files to microsodt (or others). PLEASE DO NOT SEND MY PROGRAM TO MICROSOFT (or any other company)
- In particular, the automatic update system will likely cause windows defender to mark the files as a virus. Here are the steps of how the updater works to explain why:
   1) Check my GitHub VERSION.json file for newest version
   2) Download the newest version from Released into the temp folder with a temporary name
   3) The new file is launched, renamed to the normal name, moved to the current files directory, and overwrites the exisitng file
   4) This behavior can be seen as code injection and similar, so the computer will prevent it from running. You should see a windows defender popup in the corner, click that.
   5) Look for a button/link to choose an action, click to allow it to run. Then there should be a button below that area to start actions.
   6) Relanch the app and everything should then update like normal
- For the normal "Allow program to run" popup, you can click "more info" and run/allow them.
- I built these from scratch in python for my friends and I to use, I assure you there are no viruses here.
- I have created a file here called AUTO_UPDATER_SNIPPET that shows the exact code used in the auto-updater (from version 1.0.3) to ease your mind.
- If you want to avoid all of this you can download directly from Releases to the right of this page

# Cloud_Chat
Instructions for Cloud_Chat

1) On the right side of this page click "Releases" to see the newest version
2) One person downloads the .exe files for the server and client (nothing installs, just run the .exe files)
3) Everyone else only needs to download the .exe file for the client (nothing installs, just run the .exe file)
4) There is an auto-update option starting at version 1.0.2 that checks for new versions. The update is automatic and replaces the old file.
5) The person with the server must go into their router and port forward a port to use (default is 4444)
6) There will be a popup blocking the file, click to run it anyway. I built this by hand, trust me there's no viruses here.
7) The person with the server:
   a) Can leave server ip at the deafult (all 0s)
   b) Make sure the server port is same as the port that was forwarded in router
   c) Using their client, copy the local IP at the top and give it to the other users
   d) Connect server
8) All Clients:
   a) Enter the server IP and click the update button
   b) Enter the server port and click the update button
   b) Enter a name so the server can identify you
   b) Connect to server
9) When finished, disconnect, shutdown, and close
10) A JSON file is created on close to save the last information entered. If you run into issues or (if there's an update) delete the old JSON file to prevent errors.

Version 1.06

- Client Size: 30.4 MB
- Server Size: 13.7 MB


- Allows many to many voice communication and text chat
- Server can launch on home computer (port forward is only needed on server's host system, default is 4444)
- Both server and client have an options menu for selecting IP, socket, and more
- Editable Target IP and socket on client
- Servers have optional password protection (new in Version 1.05)
- Client and Server automatically saves IP, socket, and name data into a JSON file located in Cloud_Chat.exe directory
- Server also automatically saves timeout settings
- Client inputs a user name (shown on server)
- Clients can view all server clients in options menu (new in Version 1.05)
- Clients have voice notifications (toggle in options) (new in Version 1.05)
- Includes outgoing mic sound slider
- Has mic check button

# Cloud_Chat_1on1
Instructions for Cloud_Chat_1on1

1) This is for 1-1 conversations
2) Both users must go into their router and port forward a port to use (default is 4444). To make it so only one person needs to do this, use Cloud_Group_Chat instead
3) Both users download the client .exe file (nothing installs, just run the .exe file)
4) There will be a popup blocking the file, click to run it anyway. I built this by hand, trust me there's no viruses here.
5) Enter Eachother's Local IP's and click Update button
6) Enter Eachother's forwarded port and click Update button
7) Both clients enter the same password
8) Click connect

Version 1.00

- Size: 15.6 MB
- Allows 1-1 voice communication
- Editable Target IP and socket (both parties port forward the socket using UDP, default is 4444)
- uses password-protected AES encryption (both parties put in same password)
- Automatically saves last communication data into a JSON file located in Cloud_Chat.exe directory
- set IP to your local IP shown at the top to test microphone

See change log for more info
