![Screenshot (155)](https://github.com/Aayussh004/xenonstack_linux_assessment/assets/76591635/60d228eb-bddc-4753-a5d9-d27ccb33bd7f)# xenonstack_linux_assessment
It is the technical assessment in which I have create custom linux command
# Linux Custom Command
XenonStack technical assessment for custom linux commands

# internsctl - Custom Command
internsctl is a custom command designed to perform various system operations and information retrieval tasks, simplifying administrative tasks and providing insights into system resources and users.

## Functionalities:
### User Operations:

createUser <username>: Creates a new user if it doesn't exist.
listRegularUsers: Lists regular users present on the system.
listSudoUsers: Lists users with sudo privileges.
### System Information:

cpu getinfo: Displays CPU information using lscpu.
memory getinfo: Shows memory information using free.
### File Information:

file getinfo [options] <file-name>: Provides detailed information about a specified file.
--size, -s: Print file size.
--permissions, -p: Display file permissions.
--owner, -o: Show file owner.
--last-modified, -m: Print last modified details.
## Usage:
To see the manual: internsctl man
To display the version: internsctl --version
For help on commands: internsctl --help
## Setting up as a Custom Command:
To use internsctl as a custom command:

Clone the repository or download the internsctl.sh file to your local system.
Make the script executable: chmod +x internsctl.sh
To run the command globally, move the file to a directory listed in your system's PATH. Example: /usr/local/bin/
You can use this command to move this file to system directory:
sudo mv internsctl.sh /usr/local/bin/internsctl
## Example Usage:
bash
Copy code
./internsctl.sh user create Ayush
./internsctl.sh user list
./internsctl.sh user list --sudo-only
./internsctl.sh cpu getinfo!
./internsctl.sh file getinfo --size hello.txt

## Here are the attached screenshots of the file:
![Screenshot (154)](https://github.com/Aayussh004/xenonstack_linux_assessment/assets/76591635/a6001c0b-94df-4a89-b2ef-19fde972b39b)
![Screenshot (153)](https://github.com/Aayussh004/xenonstack_linux_assessment/assets/76591635/dbd189d3-2ad6-4f68-b7f5-4fcb94b6192c)
![Screenshot (151)](https://github.com/Aayussh004/xenonstack_linux_assessment/assets/76591635/7df13321-3f88-4bbf-85b7-e9b7e07562d4)
