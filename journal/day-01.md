# Day 1 - Network design

## Why separate VLANs?

If one VLAN is down or compromised it does not affect the other ones. Traffic between VLANs must go through a router or firewall, where you can set rules (ACLs) to control who can reach what. It reduces broadcast traffic since every network has its own broadcast domain. It's easier and more secure to make changes since you don't affect the other systems. Network Settings might need to be different by type of data, this allows changes with no problem.

## Commands I learned today

- `pwd`
- `cd`
- `ls -la`
- `mkdir` 
- `touch` 
- `mv`
- `git clone` 
- `ssh-keygen` 