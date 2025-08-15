# Task 8: Identify and Remove Suspicious Browser Extensions (VPN Privacy & Setup)

## 📌 Objective
Understand the role of VPNs in protecting privacy and secure communication.

---

## 🛠 Tools Used
- **ProtonVPN Free Tier** 🌐
- **Windscribe Free** 🌍
- Website: [**WhatIsMyIPAddress.com**](https://whatismyipaddress.com) 🔍
- Website: [**DNSLeakTest.com**](https://dnsleaktest.com) 🛡️
- Website: [**SpeedTest**](https://www.speedtest.net/)

---

## 📋 Steps Followed

### 1️⃣ Choose a VPN Service
I selected **ProtonVPN Free** for its no-data-cap policy and strong privacy features.

![VPN Selection](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/vpn_selection.png)

---

### 2️⃣ Sign Up & Install
- Created a free ProtonVPN account.
- Downloaded and installed the app on Windows.

![VPN Install](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/vpn_install.png)

---

### 3️⃣ Connect to a VPN Server
- Used "Quick Connect" to join the nearest free server.
- Verified connection in the ProtonVPN app.

![VPN Connection](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/vpn_connection.png)

---

### 4️⃣ Verify IP Address Change
- Checked IP before connecting to VPN:
  - **Before:** `157.119.45.86` 

     city - Wadala

     ISP - Oneott Intertainment

    ![IP Before](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/ip_before.png) 
    
- Checked IP after connecting to VPN:
  - **After:** `185.177.125.201` 
  
       New City - Naaldwijk 

       New ISP - WorldStream B.V. 

    ![IP After](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/ip_after.png)

---

### 5️⃣ Confirm Encryption
- Ensured all browsing was over HTTPS 🔒.
- Performed a DNS leak test; results matched VPN provider’s servers.

  ![DNS Leak Test](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/dns_leak_test.png)

---

### 6️⃣ Speed Comparison
| Test          | Ping (ms) | Download (Mbps) | Upload (Mbps) |
|---------------|-----------|-----------------|---------------|
| Without VPN   | 03        | 38              | 39            |
| With VPN      | 453        | 25              | 31             |

![Speed Test](https://github.com/shindeharsh3399/Task-8-Identify-and-Remove-Suspicious-Browser-Extensions/blob/main/screenshots/speed_test.png)

---

## 📖 VPN Benefits

  - 🔐 Encrypts internet traffic – Protects data from hackers, ISPs, and snoopers using strong encryption.

  - 🌍 Masks real IP address – Hides your location and identity by showing the VPN server’s IP instead.

  - 🛡️ Secures public Wi-Fi – Prevents theft of passwords, banking info, and personal data on open networks.

  - 🚫 Reduces ISP tracking – Stops ISPs from logging and selling your browsing history.

  - 📶 Bypasses geo-restrictions – Lets you access region-locked sites, apps, and streaming content

---

## ⚠️ VPN Limitations

  - 📉 Reduced speed – Encryption and rerouting can slow download/upload speeds.

  - 🛑 Blocked services – Some websites and streaming platforms detect and block VPN IPs.

  - 🤝 Trust required – Your VPN provider handles your traffic, so it must be reliable and privacy-focused.

  - ❌ Not fully anonymous – VPN hides your IP but doesn’t make you invisible; sites you log into still know it’s you.

---

## 📷 Screenshots Folder Structure
  
    │ README.md
    └─── screenshots/
        │ vpn_selection.png
        │ vpn_install.png
        │ vpn_connection.png
        │ ip_before.png
        │ ip_after.png
        │ dns_leak_test.png
        │ speed_test.png

---


## ✅ Conclusion
A VPN is an essential tool for anyone concerned about privacy and security online. It encrypts your data, hides your real location, and safeguards you on untrusted networks like public Wi-Fi. In this task, ProtonVPN successfully masked my IP, encrypted my browsing, and prevented DNS leaks, meeting the privacy goals outlined in the objective. However, speed reduction and the need to trust the provider are important trade-offs to consider.

---
