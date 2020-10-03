SERVER ACCESS
To access the server normally, run the "AccessServer.ps1" script
When it asks for credentials, enter the crafter password
Then, when in Minecraft, add a server with the address of "localhost:1234"

SERVER ACCESS NOTES
This PowerShell window must be kept open while you play Minecraft
If you close this window on accident or on purpose, you will lose connection to the server

CONSOLE ACCESS
To access the server console, run the "ViewVNC.ps1" script
When it asks for credentials, enter the crafter password
Open VNC viewer, and enter the VNC server address of "localhost:4321"
When prompted for a password, enter the admin password
If a console is not already open, and you need to start the server, open terminal and run the below commands
  'cd /home/Crafter/Minecraft_Server/Scripts'
  './StartCraft.sh'

CONSOLE ACCESS NOTES
The VNC window can be opened and closed as you please
The PowerShell window must be kept open while the VNC is open
The VNC windows can be closed after starting the server, with no consequences
