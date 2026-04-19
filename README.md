# 🌐 NetPractice

> *An introduction to computer networking through hands-on subnet configuration — part of the 42 curriculum.*

---

## 📖 About

NetPractice is a practical networking exercise where you configure real (simulated) network topologies across 10 progressively harder levels. Starting from basic IP and subnet mask calculations, you work your way up to multi-router setups where you need to think in terms of routing tables and traffic flow.

No coding involved — just networking logic, patience, and a solid understanding of how packets actually travel across a network.

---

## 🧠 What You'll Learn

- How IP addresses and subnet masks work together
- CIDR notation and subnetting
- How switches and routers differ
- Configuring routing tables so hosts can reach each other
- Debugging unreachable hosts by tracing the packet path

---

## 🚀 Getting Started

1. Download the project files from the 42 intranet
2. Extract the archive as described in the subject PDF
3. Open `index.html` in your browser
4. Enter your 42 login and start from Level 1
5. After completing each level, click **"Get my config"** to download the `.json` file
6. Submit all 10 `.json` files along with this README in your Git repo

---

## 📁 Submission

Your repo should contain:
```
net_practice/
├── README.md
├── level1.json
├── level2.json
├── ...
└── level10.json
```

---

## 📚 Resources

**TCP/IP Protocol**
- [Video — TCP/IP explained](https://www.youtube.com/watch?v=OTwp3xtd4dg)
- [Introduction to TCP/IP](https://www.internalpointers.com/post/introduction-tcp-ip-protocol)
- *How Linux Works* — Chapter 9

**Subnet Masks**
- [Subnet Mask Cheat Sheet](https://dnsmadeeasy.com/resources/subnet-mask-cheat-sheet)
- *How Linux Works* — Chapter 9

**CIDR**
- [CIDR — Wikipedia](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)

---

## 💡 Tips

- Work backwards from the goal: figure out which hosts need to talk, then figure out what subnet connects them
- When stuck, trace the full path a packet would take — where does it break?
- AI is genuinely useful here for explaining *why* something is wrong, not just what the answer is

---

*Made with lots of coffee and debugging at 42 Beirut* ☕
