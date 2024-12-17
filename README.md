# FutureDNS

[![Liberapay patrons](https://img.shields.io/liberapay/patrons/future_dns.svg?logo=liberapay)](https://liberapay.com/future_dns/)

A privacy-focused DNS service that prioritizes security, speed, and user anonymity.

## Server Locations

| Location | 🇩🇪 Germany | 🇺🇸 United States |
|----------|------------|-----------------|
| IPv4 | `162.55.52.228` | `5.161.67.176` |
| IPv6 | `2a01:4f8:1c1c:adbc::` | `2a01:4ff:f0:87a2::` |
| DNS over HTTPS | `https://dns.de.futuredns.eu.org/dns-query/` | `https://dns.us.futuredns.eu.org/dns-query` |
| DNS over TLS | `tls://dns.de.futuredns.eu.org` | `tls://dns.us.futuredns.eu.org` |
| DNS over QUIC | `quic://dns.de.futuredns.eu.org` | `quic://dns.us.futuredns.eu.org` |

## Features

- **Complete Privacy**: Strict no-logging policy ensures your DNS queries remain private
- **Enhanced Security**: Built-in protection against ads, trackers, and malware
- **Multiple Protocols**: Supports DNSSEC, DoT (DNS over TLS), DoH (DNS over HTTPS), and DoQ (DNS over QUIC)
- **Global Servers**: Strategically located servers for optimal performance

## Resolver Configuration

FutureDNS uses direct recursive resolution via Unbound on our VPS servers, without relying on any third-party upstream providers. This ensures complete control over DNS resolution and maintains user privacy.

### Blocklists

We utilize several curated blocklists to protect users from ads, trackers, malware, and phishing:

- [AdGuard DNS filter](https://adguardteam.github.io/HostlistsRegistry/assets/filter_1.txt)
- [AdAway Default Blocklist](https://adguardteam.github.io/HostlistsRegistry/assets/filter_2.txt)
- [Phishing Army](https://adguardteam.github.io/HostlistsRegistry/assets/filter_18.txt)
- [Dandelion Sprout's Anti-Malware List](https://adguardteam.github.io/HostlistsRegistry/assets/filter_12.txt)
- [URLHaus Malicious URL Blocklist](https://adguardteam.github.io/HostlistsRegistry/assets/filter_11.txt)
- [PhishTank and OpenPhish URL Blocklist](https://adguardteam.github.io/HostlistsRegistry/assets/filter_30.txt)
- [OISD Blocklist Big](https://adguardteam.github.io/HostlistsRegistry/assets/filter_27.txt)
- [HaGeZi's Normal Blocklist](https://adguardteam.github.io/HostlistsRegistry/assets/filter_34.txt)
- [Dandelion Sprout's Anti Push Notifications](https://adguardteam.github.io/HostlistsRegistry/assets/filter_39.txt)
- [1Hosts (Lite)](https://adguardteam.github.io/HostlistsRegistry/assets/filter_24.txt)

### Allowlists

To prevent over-blocking, we implement these allowlists:

- [anudeepND Whitelist](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt)
- [Falukorv List](https://raw.githubusercontent.com/DandelionSprout/adfilt/master/FalukorvList.txt)

Have suggestions for additional blocklists or allowlists? [Let us know](mailto:contact@futuredns.eu.org)!

## DNS Leak Testing

We recommend regularly testing your DNS configuration to ensure your privacy is maintained. You can use these trusted services to verify your DNS setup:

- [DNS Leak Test](https://www.dnsleaktest.com)
- [IP Leak](https://ipleak.net)
- [BrowserLeaks DNS Test](https://browserleaks.com/dns)

Run these tests both before and after configuring FutureDNS to ensure your queries are properly routed through our servers.

## Service Status

You can check our service status at any time by visiting:
[status.futuredns.eu.org](https://status.futuredns.eu.org/)

## Contact

For support or inquiries:
- Email: [contact@futuredns.eu.org](mailto:contact@futuredns.eu.org)
- Twitter: [@futurednseuorg](https://x.com/futurednseuorg)
- Support us: [Liberapay](https://liberapay.com/future_dns/)

## Privacy Policy

FutureDNS operates with a strict no-logging policy. We do not store or process any personal data or DNS queries. Your privacy is our top priority.

---

More locations coming soon! Stay tuned for additional servers worldwide. 🌍
