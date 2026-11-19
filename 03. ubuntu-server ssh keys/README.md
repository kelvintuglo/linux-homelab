November 19,2026

Lab 03: ubuntu server ssh keys

Goal: Build an ubuntu server VM and practice how to connect to it remotely using ssh.

Setup

- Host: HP Elitebook 8460p laptop running Ubuntu 24.04 LTS
- VM software: Oracle VirtualBox
- Guest: Ubuntu Server 26.04.1 LTS
- Network: NAT with a port-forward rule (host: tugy host ip: 127.0.0.1: host port: 2222 to guest port: 22)

What I Did:

- Created a "pre ssh" snapshot before connecting remotely using ssh.
- Checked the .ssh folder to see if there were already generated keys and there was none
- Generated the ssh keys
- Copied the public key onto the server (VM)
- Logged in remotely to the VM
