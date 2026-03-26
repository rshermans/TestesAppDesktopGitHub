## 2025-03-24 - [Resource Prioritization]
**Learning:** Adding `preconnect` and `dns-prefetch` hints for external CDNs (like Bootstrap) can significantly reduce the connection setup time (DNS/TCP/TLS) and overall load time by initiating the handshake early.
**Action:** Always check for external resource dependencies and add appropriate resource hints.
