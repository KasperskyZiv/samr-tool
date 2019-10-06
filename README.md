![](cymptom_logo.svg)
&nbsp;

# Cymptom Candidate Task

## MSRPC using Python
In the following task you’re going to use MSRPC protocol (Microsoft implementation of DCERPC) in order to manage a remote Windows machine. 

In specific, you will use MS-SAMR API which provides managements functionality for an
account store or directory. You will find any information regarding the interface in the following https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-samr/4df07fab-1bbc-452f-8e92-7853a3c7e380[link].
You are not required to implement the whole MS-SAMR interface. Most of the work was already done
for you by https://github.com/SecureAuthCorp/impacket[Impacket] project. The project contains an implementation for most MSRPC interfaces with examples and test cases.
Your code should support the following:
1. Create a new local user\group
2. Retrieve all users\groups
3. Delete a user\group

The code should request the user for a command to execute and the system will operate accordingly.
For start, try to implement a piece of code for the following https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-samr/3d8e23d8-d9df-481f-83b3-9175f980294c[example]. This example emphasizes the
sequence of methods required to create a user account on a remote system. You need to
understand each function, how it works, and the relevant structures involved.
Next, extend it to fully support all the functionality required.

### Requirements
- You should be using Python 3.6+
- You should work with GitHub repository to store and manage your code.
- You are required to write your code using OOP concepts
- Document your code as much as needed

### Before starting this task
- Fork this repository ([https://github.com/cymptomlabs/candidate-task.git](https://github.com/cymptomlabs/candidate-task.git)).
- Send a link to the forked github repository to: itamar@cymptom.com .

**Good luck!**
