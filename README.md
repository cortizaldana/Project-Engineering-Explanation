# Project-Engineering-Explanation

# The Foundation

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


