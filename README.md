
## Disclaimer

This script is provided "as is" without any warranty of any kind, either express or implied. The use of this script is at your own risk. The author is not responsible for any damage or loss of data that may occur as a result of using this script. By using this script, you agree to these terms.

### If you found [this repository](https://github.com/TzurSoffer/WindowsPasswordBypasser) useful, please give it a ⭐!.

## About:
A badUSB script that gains full admin access to a windows machine from the login screen.

## Note for pico-ducky
Must use [my fork](https://github.com/TzurSoffer/pico-ducky/tree/main) of the pico-ducky as it supports holding and releasing keys.

### How it works:
1. It reboots into safe mode
2. It opens a cmd from safe mode
3. It changes the Utilman.exe to be a cmd.exe
4. It boots back into windows
5. It opens the help menu which has been replaced with a cmd instance
6. It creates a new admin account named ```rubberDucky``` with the password ```1234```
7. It logs into the new account
