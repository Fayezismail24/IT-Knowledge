DNS records are the settings that tell the internet how your domain behaves, Think of them as instructions inside your domain’s control panel

🟦 1. A Record — IPv4 Address

Maps a domain → IPv4 address

example.com → 192.168.1.10

Used for: Websites Servers Subdomains

--------------------------------------------------------------------------------------------------------------------------------------------

🟫 2. PTR Record — Reverse DNS

Maps an IP → domain
(used by email servers and networks)

192.168.1.10 → mail.example.com

--------------------------------------------------------------------------------------------------------------------------------------------


🟩 3. AAAA Record — IPv6 Address

Maps a domain → IPv6 address


example.com → 2001:db8:abcd::1

--------------------------------------------------------------------------------------------------------------------------------------------

🟧 4. CNAME — Alias Record

Points a domain to another domain (not an IP)

Real example let say my page is → fayez.github.io

but people know my website as  www.fayez.com  

www.fayez.com → CNAME → fayez.github.io


--------------------------------------------------------------------------------------------------------------------------------------------

🟥 5. MX Record — Email Routing

Defines where emails should be delivered

example.com → mail.google.com (priority 10)


Used for Gmail, Outlook, Zoho, etc.

--------------------------------------------------------------------------------------------------------------------------------------------



🟪 6. TXT Record — Verification & Security

Stores text information for:

SPF DKIM

DMARCDomain verification

Examples:

SPF:

v=spf1 include:_spf.google.com ~all


Google verification:

google-site-verification=ABC123XYZ

--------------------------------------------------------------------------------------------------------------------------------------------


🟨 7. NS Record — DNS Provider

Specifies the authoritative name servers.

ns1.cloudflare.com
ns2.cloudflare.com


Changing NS moves the domain to another DNS host.

--------------------------------------------------------------------------------------------------------------------------------------------




🟦 8. SRV Record — Service Location

Defines service, port, and protocol.

_sip._tcp.example.com → sipserver.example.com port 5060


Used for:

SIP

Zoom

Microsoft services

Minecraft servers

--------------------------------------------------------------------------------------------------------------------------------------------


⚪ 9. SOA Record — Domain Authority Info

Contains admin details:

Primary name server

Contact email

Serial number

Refresh timers

Automatically exists for every domain.

--------------------------------------------------------------------------------------------------------------------------------------------


🔵 10. CAA Record — SSL Control

Specifies which Certificate Authorities can issue SSL certificates.

example.com → issue "letsencrypt.org"


Improves security.


CAA	SSL authority control

