# 📂 SOHO Router Configuration and Network Verification using OpenWrt

<details>
<summary>📘 <strong>Project Overview</strong></summary>

As part of my CompTIA A+ Core 1 studies at Western Governors University (WGU), I completed a hands-on lab to configure and verify a Small Office/Home Office (SOHO) network using OpenWrt firmware. This project involved setting up wired and wireless connections, confirming DHCP lease assignments, ensuring Internet and DNS access, and reviewing firewall settings.

</details>

<details>
<summary>🎯 <strong>Objectives Covered</strong></summary>

- Install and configure basic wired/wireless SOHO networks  
- Verify client device connectivity through DHCP  
- Test Internet and DNS functionality using diagnostic tools  
- Confirm wireless network setup and stability  
- Review firewall and security configurations to protect internal resources  

</details>

<details>
<summary>🛠️ <strong>Tools Used</strong></summary>

- OpenWrt Web Interface (LuCI)  
- GNS3 Network Simulation Software  
- OpenWrt Diagnostics Tools (Ping, Traceroute)  

</details>

<details>
<summary>⚙️ <strong>Configuration and Setup Steps</strong></summary>

- Accessed OpenWrt router at `192.168.1.1`  
- Configured LAN settings and enabled the DHCP server  
- Set up WPA2-protected wireless access points  
- Connected multiple wired and wireless devices  
- Verified proper IP address assignments via DHCP  
- Conducted ping tests to verify LAN, Internet, and DNS connectivity  
- Reviewed firewall zone rules for security  

</details>

<details>
<summary>🔍 <strong>Verification Process</strong></summary>

**✅ Connected Devices Check**  
→ Status → Overview → Confirmed DHCP leases  

**✅ Wireless Clients Check**  
→ Status → Wireless → Verified client signal and encryption  

**✅ Internet/DNS Test**  
→ Network → Diagnostics → Pinged:
- `192.168.1.1` (router)
- `8.8.8.8` (external IP)
- `google.com` (domain resolution)

**✅ DHCP Server Check**  
→ Network → Interfaces → LAN → DHCP settings reviewed  
→ Network → DHCP and DNS → Lease table verified  

**✅ Firewall Check**  
→ Status → Firewall → Verified LAN → WAN forwarding and default security

</details>

<details>
<summary>🖼️ <strong>Screenshots</strong></summary>

> 📸 Active DHCP leases  
> 📸 Wireless client list  
> 📸 Successful ping results  
> 📸 DHCP settings  
> 📸 Firewall zone overview  

(Insert or link screenshots here if stored in your repo)

</details>

<details>
<summary>🧠 <strong>Reflection</strong></summary>

When I first started this lab, the number of settings in OpenWrt felt overwhelming. But step by step, I learned how to navigate and configure essential networking features like DHCP, firewall zones, and wireless security.  
Now that I’ve built and verified this network from scratch, I’m way more confident with SOHO setups and basic troubleshooting. 

</details>
