# About this project
Bypass check if user has a real microsoft account linked with the launcher<br>
⚠️ This is for entertainment purposes only ⚠️

# Before installation
If you have some accounts saved then executing this script will remove them!<br>

# Usage
Download the latest version of ATLauncher from https://atlauncher.com/, install it then go in terminal and execute this command:
### Windows CMD:
```
echo [{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOUR-USERNAME-HERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}] > %appdata%/ATLauncher/configs/accounts.json
```
### Linux Shell:
```
echo '[{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOUR-USERNAME-HERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}]' > ~/.local/share/ATLauncher/configs/accounts.json
```

# Usage for Portable version
Download the portable version of ATLauncher then execute this command in terminal:
### Windows Portable (cd to installation path) CMD:
```
echo [{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOUR-USERNAME-HERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}] > configs/accounts.json
```
### Linux Portable (cd to installation path) Shell:
```
echo '[{"accessToken":"0","mustLogin":true,"username":"00000000-0000-0000-0000-000000000000","minecraftUsername":"YOUR-USERNAME-HERE","uuid":"00000000000000000000000000000000","collapsedPacks":[],"collapsedInstances":[],"collapsedServers":[],"internalType":"com.atlauncher.data.MicrosoftAccount"}]' > configs/accounts.json
```

After that you can download an instance and then you need to CLICK THE TRIANGLE on the right of the PLAY BUTTON and select "Play Offline". Type in your desired username and go do whatever you want idc.

# What not to do
Don't delete the default offline account in the accounts tab, it removes the *magic*

# Manual Installation
There is a file in repo called "accounts.json" [here](https://raw.githubusercontent.com/antunnitraj/ATLauncher-Offline-Bypass/main/accounts.json) and you need to download it to this place:
### ATLauncher
* Windows: `%appdata%/ATLauncher/configs/`
* Linux: `~/.local/share/ATLauncher/configs/`

### Portable ATLauncher
`PATH_TO_INSTALLATION/configs/`
