# Project-Engineering-Explanation


<img width="907" height="480" alt="Screenshot from 2026-02-09 10-44-12" src="https://github.com/user-attachments/assets/308969ff-e099-495d-9af3-7c0ca6ee2cf3" />


# The Foundation

- KVM/QEMU
- Virtualizing everything
- Keeps cost down

# Network Segmentation 

- Bridges will act like a network subnet
- Each bridge will have virtual machines/services running
- Each bridge will live in a single firewalld zone for easy management 
- The key is to split the network into multiple to avoid traffic congestion
- Keeps it nice and clean

# Network Address Translation

- Bridges need to communicate to the outside world
- Traffic from the bridge will exit out from the host machine
- Rules will be implemented via Firewalld using policies


