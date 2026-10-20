# Bandit Level 0: SSH Connection

# Objective
Learn how to connect to a remote server using SSH(Secure Shell).

# Concepts Learned
* SSH provides the secure connections to a remote system.
* A port number can be specified when connecting to a server.

# Command used
```bash
ssh -p <port-number> <username>@<server-address>
```

# Command Explanation
- `ssh`: Estabishes a secure connection to a remote server.
- `-p`: Specifies the port number.
- `<username>`: The account used to log in.
- `<server-address>`: The hostname or IP address of the remote server.

# My Approach
1. used SSH to connect to Bandit server.
2. Entered the password when prompted.
3. Used exit to close the SSH session and return to my local terminal.

# What I Learned
I learned how to connect to a rmote server using SSH and how to specify a port with -p option.
I faced some difficulty when using SSH for the  first time , so I paln to practise it further.

# Reference
* OverTheWire:Bandit
