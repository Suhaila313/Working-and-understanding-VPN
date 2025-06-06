# VPN Privacy & Performance Test Report

A hands-on analysis of ProtonVPN's free tier, testing IP masking, encryption, speed impact, and DNS security.

# Report Contents
1. Introduction: VPN purpose and setup.
2. Step-by-Step Setup: Screenshots of installation/connection.
3. Tests:
   - IP/DNS leak tests.
   - HTTPS encryption verification.
   - Speed comparisons (with/without VPN).
4. Encryption Analysis: WireGuard vs. OpenVPN.
5. Conclusion: Benefits and limitations.

 Key Findings
 # Successes:
- No IP/DNS leaks detected.
- Traffic fully encrypted through VPN.
- Effective geo-spoofing (Netherlands server).

# Limitations:
- 42% slower download speeds with VPN.
- Google loaded as HTTP (no padlock) due to caching.

# Tools Used
- VPN: [ProtonVPN Free Tier](https://protonvpn.com/free-vpn)
- IP Tests: [WhatIsMyIPAddress](https://whatismyipaddress.com), [DNSLeakTest](https://www.dnsleaktest.com)
- Speed Test: [Speedtest by Ookla](https://speedtest.net)

# How to Use This Report
1. Clone the repo.
2. Open `VPN_Report.pdf` for full analysis.
3. Refer to screenshots in `/images` folder.

# Why This Matters
Demonstrates practical trade-offs between privacy (VPN encryption) and performance (speed loss). Useful for cybersecurity students and privacy-conscious users.

- Report by Suhaila P.S
