
# Cloud_Group_Chat
Instructions for Cloud_Group_Chat

1) One person downloads the .exe files for the server and client (nothing installs, just run the .exe files)
2) Everyone else only needs to download the .exe file for the client (nothing installs, just run the .exe file)
3) There will be a popup blocking the file, click to run it anyway. I built this by hand, trust me there's no viruses here.
4) The person with the server must go into their router and port forward a port to use (default is 4444)
5) The person with the server:
   a) Can leave server ip at the deafult (all 0s)
   b) Make sure the server port is same as the port that was forwarded in router
   c) Using their client, copy the local IP at the top and give it to the other users
   d) Connect server
6) All Clients:
   a) Enter the server IP and click the update button
   b) Enter the server port and click the update button
   b) Enter a name so the server can identify you
   b) Connect to server
7) When finished, disconnect, shutdown, and close
8) A JSON file is created on close to save the last information entered. If you run into issues or (if there's an update) delete the old JSON file to prevent errors.

Version 1.01

- Server Size: 10.8 MB
- Client Size: 24.1 MB

- Allows many to many voice communication
- Server can launch on home computer (port forward is only needed on server's host system, default is 4444)
- Editable Target IP and socket on client
- This version does not use password protection (yet)
- Client automatically saves last communication data into a JSON file located in Cloud_Chat.exe directory
- Client inputs a user name (shown on server)
- Includes outgoing mic sound slider
- Has mic check button

# Cloud_Chat
Instructions for Cloud_Chat

1) This is for 1-1 conversations
2) Both users must go into their router and port forward a port to use (default is 4444). To make it so only one person needs to do this, use Cloud_Group_Chat instead
3) Both users download the client .exe file (nothing installs, just run the .exe file)
4) There will be a popup blocking the file, click to run it anyway. I built this by hand, trust me there's no viruses here.
5) Enter Eachother's Local IP's and click Update button
6) Enter Eachother's forwarded port and click Update button
7) Click connect

Version 1.00

- Size: 15.6 MB
- Allows 1-1 voice communication
- Editable Target IP and socket (both parties port forward the socket using UDP, default is 4444)
- uses password-protected AES encryption (both parties put in same password)
- Automatically saves last communication data into a JSON file located in Cloud_Chat.exe directory
- set IP to your local IP shown at the top to test microphone

See change log for more info
