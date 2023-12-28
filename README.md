# LinuxCustomScript
custom script creation task 


# linux custom script

# internsctl

## Overview

- `internsctl` is a custom Linux command for system-related operations.
- Provides CPU, memory, user management, and file information functionalities.

## Features

- **Version:** v0.1.0
- **Author:** Samadhan patil
- 

## Usage

### Installation
  cd internsctl
  chmod +x internsctl
Commands
Display version:

bash
Copy code
./internsctl --version
Display help:

bash
Copy code
./internsctl --help
CPU Information:

bash
Copy code
./internsctl cpu getinfo
Memory Information:

bash
Copy code
./internsctl memory getinfo
User Management:

Create a new user:

bash
Copy code
./internsctl user create <username>
List all users:

bash
Copy code
./internsctl user list
List users with sudo permissions:

bash
Copy code
./internsctl user list --sudo-only
File Information:

Get information about a file:

bash
Copy code
./internsctl file getinfo <file-name>
Get specific information about a file:

bash
Copy code
./internsctl file getinfo --size <file-name>
./internsctl file getinfo --permissions <file-name>
./internsctl file getinfo --owner <file-name>
./internsctl file getinfo --last-modified <file-name>


Draw.io Diagrams
Workflow Diagram
