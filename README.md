_________________________________________________________________________________________________________________________________________________________________________
WINDOWS

first you open your spotify then you minimize it and open a shell window (PowerShell)
with CTRL+C and CTRL+V you copy the link into the shell window and press enter once and wait until it has processed all commands
*Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1" | Invoke-Expression*

when that's done, copy the next link just like before and confirm with enter
*Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/spicetify/spicetify-marketplace/master/install.ps1" | Invoke-Expression*
_________________________________________________________________________________________________________________________________________________________________________
Linux+MacOS

first you open your spotify then you minimize it and open shell
with CTRL+C and CTRL+V you copy the link into the shell window and press enter once and wait until it has processed all commands
*curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh*

when that's done, copy the next link just like before and confirm with enter
*curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/install.sh | sh*
_________________________________________________________________________________________________________________________________________________________________________ 
