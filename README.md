# Networking-Interview-Questions

1. OSI Layers
2. TCP/IP
3. Http, https: Sends web data without encryption; HTTPS: HTTP secured with TLS encryption, providing confidentiality, integrity, and server authentication.
4. FTP 20/21 | SSH 22 | Telnet 23 | SMTP 25 | DNS 53 | DHCP 67/68 | HTTP 80 | HTTPS 443 | POP3 110 | IMAP 143
5. Traceroute - each hop along the destination and total response time at each hop
6. SSH → Secure remote login/access to another machine
7. SSL/TLS → Encrypts communication between applications over a network (e.g., HTTPS).
8. Https works

<img width="1024" height="663" alt="image" src="https://github.com/user-attachments/assets/466525a0-0fa5-4c92-b974-4055c61526a3" />
9. VPN → Protects/reroutes your whole device’s traffic.
  Example: Turn on a VPN → Chrome, Spotify, etc. send internet traffic through the VPN.
10. Proxy → Middleman for specific traffic/app.
  Example: Configure a proxy in Chrome → Chrome requests go Chrome → Proxy → Website.
Easy memory: VPN = whole device 🔒 | Proxy = middleman for selected traffic 🔄
11. Forward Proxy → Hides/protects the client from the server.
Example: You → Proxy → Google → Google sees the proxy, not you.
Reverse Proxy → Hides/protects backend servers from the client.
Example: You → Nginx → Backend Server 1/2/3 → You interact with Nginx, not the backend directly.
12. CDN (Content Delivery Network) → Stores/caches website content on servers closer to users so it loads faster.
13. Firewall → Monitors and allows/blocks network traffic based on security rules.
14 Main types to remember
- Packet-filtering firewall → Checks IP, port, protocol and allows/blocks packets.
- Stateful firewall → Tracks active connections and decides based on connection state.
- Proxy/Application firewall → Inspects application-level traffic such as HTTP.
- NGFW (Next-Generation Firewall) → Deep inspection + application awareness + intrusion prevention.
- WAF (Web Application Firewall) → Protects web applications/HTTP(S) from attacks such as SQL injection and XSS.
