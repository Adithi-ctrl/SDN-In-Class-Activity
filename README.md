# SDN-In-Class-Activity
# SDN Lab Activities: Four Controller Applications on Mininet

This repository contains the code files, scripts, topology setups, and the complete report for 4 SDN In-Class Activities:

- **Task 1: Automated Network Policy Engine**
  - Uses Python `requests` with the ONOS REST API to monitor port statistics and dynamically install drop rules during peak hours.
  
- **Task 2: Broadcast-Storm Prevention with MAC Learning**
  - An `os-ken` (Ryu API) controller application that handles PacketIn events, performs source MAC learning, and installs drop rules for duplicate broadcast loops.

- **Task 3: 5G Campus Network Slicing with QoS Queues**
  - Configuration script using `ovs-vsctl` and `ovs-ofctl` to set up Linux-HTB queues on egress ports and direct traffic based on DSCP/VLAN tags[cite: 1].

- **Task 4: ONOS Intent Framework with Automatic Rerouting**
  - Submits PointToPointIntent requests with bandwidth constraints to ONOS and verifies automatic rerouting upon link failure[cite: 1].

---

### File Structure
- `task1/` — Policy engine script and Mininet topology setup[cite: 1]
- `task2/` — Loop-safe switch application and topology test script[cite: 1]
- `task3/` — QoS queue setup script and slice topology test script[cite: 1]
- `task4/` — Intent manager script and failure simulation topology[cite: 1]
- `outputs/` — Terminal output execution screenshots[cite: 1]
- `SDN_Labs_Report.docx` — Complete consolidated lab report[cite: 1]
