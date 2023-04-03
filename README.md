# About this project
Bypass check if user has a real microsoft account linked with the launcher<br>
⚠️ This is for entertainment purposes only ⚠️

# Before installation
If you have some accounts saved then executing this script will remove them!<br>

# Usage
Download the latest version of ATLauncher from https://atlauncher.com/, install it then go in terminal and execute this command (change "YOURUSERNAMEHERE" to your desired username):
### Windows CMD:
```
echo [{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOURUSERNAMEHERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}] > %appdata%/ATLauncher/configs/accounts.json
```
### Linux Shell:
```
echo '[{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOURUSERNAMEHERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}]' > ~/.local/share/atlauncher/configs/accounts.json
```

# Usage for Portable version
Download the portable version of ATLauncher then execute this command in terminal (change "YOURUSERNAMEHERE" to your desired username):
### Windows Portable (cd to installation path) CMD:
```
echo [{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOURUSERNAMEHERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}] > configs/accounts.json
```
### Linux Portable (cd to installation path) Shell:
```
echo '[{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOURUSERNAMEHERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}]' > configs/accounts.json
```
# How to use
Download an instance and then you need to CLICK THE TRIANGLE on the right of the PLAY BUTTON and select "Play Offline", then type in your desired username and enjoy!

# What not to do
Don't delete the default offline account in the accounts tab, it removes the *magic*

# Manual Installation
There is a file in repo called "accounts.json" [here](https://raw.githubusercontent.com/antunnitraj/ATLauncher-Offline-Bypass/main/accounts.json) and you need to download it to this place:
### ATLauncher
* Windows: `%appdata%/ATLauncher/configs/`
* Linux: `~/.local/share/ATLauncher/configs/`

### Portable ATLauncher
`PATH_TO_INSTALLATION/configs/`

After that you can go to that file, open it with a text editor (Notepad) and edit the value that sais "YOURUSERNAMEHERE" to your desired username
