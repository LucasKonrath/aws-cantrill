### DNS Record Types

## Nameserver (NS)
- Points to DNS servers responsible for a domain
- Delegates DNS authority to specific servers
- Required for domain delegation

## A Record
- Maps domain name to IPv4 address
- Most common DNS record type
- Example: example.com → 192.0.2.1

## AAAA Record  
- Maps domain name to IPv6 address
- IPv6 version of A record
- Example: example.com → 2001:db8::1

## CNAME (Canonical Name)
- Points domain name to another domain name
- Creates alias for existing domain
- Cannot be used for root domain
- Example: www.example.com → example.com

## MX (Mail Exchange)
- Specifies mail servers for domain
- Has priority value (lower = higher priority)
- Required for email delivery
- Example: example.com → mail.example.com (priority 10)

## TXT Record
- Stores arbitrary text data
- Used for domain verification
- Common uses: SPF, DKIM, domain ownership verification
- Example: "v=spf1 include:_spf.google.com ~all"

## TTL (Time To Live)
- Not a record type - applies to all records
- Specifies how long DNS resolvers cache the record
- Measured in seconds
- Lower TTL = faster updates, more DNS queries
- Higher TTL = fewer queries, slower updates