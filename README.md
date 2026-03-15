# Project-Engineering-Explanation





# Building The Foundation For Our Production Like Enviornement 

- I'll be relying on KVM/QEMU to virtualize everything 
- Virtualizing will keep cost down
- This project is all about building the base of our production like env to support future scaling

# Network Segmentation Through Bridging 

- Bridges will act like a network subnet
- Each bridge will have virtual machines/services running
- Each bridge will live in a single firewalld zone for easy management 
- The key is to split the network into multiple to avoid traffic congestion
- Keeps it nice and clean

# Bridge Connectivity Through Network Address Translation

- Bridges need to communicate to the outside world
- Traffic from the bridge will exit out from the host machine
- Rules will be implemented via Firewalld using policies

# Conculsion 

- This project will allow me to not only scale in the future but keep things nice and clean without having to spend money on infrastructure. I get to work with a variety of tool and come up with solutions by finding work arounds.  


