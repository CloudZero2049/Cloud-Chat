
# Cloud_Chat
Instructions for Cloud_Chat
--> On the right side of this page click "Releases" to see the newest version

1) One person downloads the .exe files for the server and client (nothing installs, just run the .exe files)
2) Everyone else only needs to download the .exe file for the client (nothing installs, just run the .exe file)
3) There is an auto-update option starting at version 1.0.2 that checks for new versions. The update is automatic and replaces the old file.
4) The person with the server must go into their router and port forward a port to use (default is 4444)
5) There will be a popup blocking the file, click to run it anyway. I built this by hand, trust me there's no viruses here.
6) The person with the server:
   a) Can leave server ip at the deafult (all 0s)
   b) Make sure the server port is same as the port that was forwarded in router
   c) Using their client, copy the local IP at the top and give it to the other users
   d) Connect server
7) All Clients:
   a) Enter the server IP and click the update button
   b) Enter the server port and click the update button
   b) Enter a name so the server can identify you
   b) Connect to server
8) When finished, disconnect, shutdown, and close
9) A JSON file is created on close to save the last information entered. If you run into issues or (if there's an update) delete the old JSON file to prevent errors.

Version 1.02

- Server Size: 13.7 MB
- Client Size: 23.9 MB

- Allows many to many voice communication and text chat
- Server can launch on home computer (port forward is only needed on server's host system, default is 4444)
- Editable Target IP and socket on client
- This version does not use password protection (planned)
- Client automatically saves last communication data into a JSON file located in Cloud_Chat.exe directory
- Client inputs a user name (shown on server)
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
