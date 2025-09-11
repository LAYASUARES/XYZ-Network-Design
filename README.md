# XYZ-Network-Design

The objective of this project is to design and implement a branch office network for XYZ Company in Bonalbo, Eastern Australia. The network must operate independently from the headquarters and meet the following requirements:

Use one Cisco router and one Cisco switch as core devices.
Create three departments (Admin/IT, Finance/HR, and Customer Service/Reception), each in its own VLAN.
Provide wireless connectivity for all departments.
Configure DHCP services to assign IPv4 addresses automatically.
Ensure full inter-department communication through inter-VLAN routing.
Implement the design using the ISP-provided base network 192.168.1.0/24.

## Requirements Met

✅ Cisco Router and Switch implemented
✅ Three departments configured in separate VLANs
✅ Wireless network available for each department
✅ DHCP configured for automatic IPv4 addressing
✅ Full inter-department communication via inter-VLAN routing

##Topologia 

<img width="830" height="591" alt="Topology" src="https://github.com/user-attachments/assets/8cc30a92-af90-4ced-83f1-8fb3e64e2fd3" />

##IP PLAN
| Departament           | VLAN | Subnet       | Gateway       |
|-----------------------|------|----------------|---------------|
| Admin/IT              | 10   | 192.168.1.0/26 | 192.168.1.1   |
| Finance/HR            | 20   | 192.168.1.64/26| 192.168.1.65  |
| Customer Service/Reception | 30   | 192.168.1.128/26| 192.168.1.129 |

##How to run the project

Just go to the configs folder and download the .pkt file, after downloading just open it, and it will open in Cisco Packet Tracer

Autor
Ladislau Alexandre. Linkedin: https://www.linkedin.com/in/ladislau-soares-alexandre-1779781ba/


