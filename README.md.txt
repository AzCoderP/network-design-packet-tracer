# 🌐 Enterprise Network Design Project

Bu layihə Cisco Packet Tracer istifadə edilərək qurulmuş, VLAN, VTP, Router-on-a-Stick və təhlükəsizlik protokolları ilə optimallaşdırılmış şəbəkə infrastrukturudur.

## 🏗️ Topologiya
![Topology Image](Topology.png)



## 🛠️ Texniki Xüsusiyyətlər
Layihədə tətbiq edilən əsas texnologiyalar:
- **VLAN & Trunking:** 802.1Q, Native VLAN (97), DTP deaktiv edilib.
- **VTP:** Domain: `mitacademy.az` (Server/Client rejimi).
- **Routing:** Router-on-a-Stick (Subinterface metodu).
- **Security:** - Port Security (Sticky MAC).
    - BPDU Guard & Portfast (Access portlarda).
    - SSH (Domain: mitacademy.az, User: netadmin).
    - DHCP Snooping.
- **Services:** Router üzərində DHCP Server və NTP Server.

## 📋 Konfiqurasiya Detalları
Tam konfiqurasiya kodlarını [Configurations/](Configurations/) qovluğundan əldə edə bilərsiniz.

---
## 👨‍💻 Author
**Polad Gonagov** Computer Engineering Student | Networking Enthusiast