# Infrastructure Reconnaissance: technovasolutions.io

## Domain Information
- **Primary Domain:** technovasolutions.io
- **Company:** [[TechNova Solutions]]
- **Reconnaissance Date:** 2026-02-03

## Subdomain Discovery

### 1. demo.technovasolutions.io
- **IP Address:** 49.13.52.164
- **Hostname:** static.164.52.13.49.clients.your-server.de
- **ASN:** 24940 (HETZNER-AS)
- **IP Range:** 49.13.0.0/16
- **Location:** Germany
- **TTL:** 24
- **Purpose:** Demo/Testing Environment

### 2. nms.technovasolutions.io
- **IP Address:** 49.13.52.164
- **Hostname:** static.164.52.13.49.clients.your-server.de
- **ASN:** 24940 (HETZNER-AS)
- **IP Range:** 49.13.0.0/16
- **Location:** Germany
- **TTL:** 24
- **Purpose:** Network Management System (NMS)

### 3. odoo17.technovasolutions.io
- **IP Address:** 5.75.231.60
- **Hostname:** static.60.231.75.5.clients.your-server.de
- **ASN:** 24940 (HETZNER-AS)
- **IP Range:** 5.75.128.0/17
- **Location:** Germany
- **TTL:** 2
- **Purpose:** Odoo 17 ERP System
- **Analysis:** Odoo is an open-source ERP/CRM platform. Version 17 indicates recent deployment.

### 4. wap.technovasolutions.io
- **IP Address:** 49.13.128.107
- **Hostname:** static.107.128.13.49.clients.your-server.de
- **ASN:** 24940 (HETZNER-AS)
- **IP Range:** 49.13.0.0/16
- **Location:** Germany
- **TTL:** 24
- **Purpose:** WAP (Wireless Application Protocol) or Web Application Portal

## Hosting Infrastructure

### Hosting Provider: Hetzner Online GmbH
- **ASN:** 24940 (HETZNER-AS)
- **Location:** Germany
- **Provider Type:** Cloud/Dedicated Server Hosting
- **Service:** your-server.de (Hetzner's dedicated server brand)

### IP Ranges Identified
1. **49.13.0.0/16** (HETZNER-AS)
   - Used by: demo, nms, wap subdomains
   - Location: Germany

2. **5.75.128.0/17** (HETZNER-AS)
   - Used by: odoo17 subdomain
   - Location: Germany

## Infrastructure Analysis

### Server Distribution
- **3 servers** in 49.13.0.0/16 range (demo, nms, wap)
- **1 server** in 5.75.128.0/17 range (odoo17)
- All hosted on Hetzner infrastructure in Germany

### Technology Stack Indicators
- **Odoo 17:** ERP/CRM system (business management software)
- **NMS:** Network Management System (infrastructure monitoring)
- **Demo Environment:** Testing/staging environment
- **WAP:** Web application or wireless access point

### Security Considerations
- **Geographic Location:** Germany (EU data protection regulations)
- **Hosting Provider:** Hetzner (reputable European provider)
- **Subdomain Exposure:** Multiple subdomains publicly accessible
- **TTL Values:** Low TTL (2-24) suggests dynamic DNS or load balancing

## Recommendations

### Further Reconnaissance
1. **Port Scanning:** Identify open ports on discovered IPs
2. **Service Enumeration:** Determine running services on each subdomain
3. **SSL Certificate Analysis:** Check certificate details and validity
4. **DNS Enumeration:** Continue subdomain discovery
5. **WHOIS Lookup:** Domain registration information
6. **Banner Grabbing:** Identify software versions

### Security Assessment
1. Check for exposed services (SSH, FTP, etc.)
2. Analyze SSL/TLS configuration
3. Review Odoo version for known vulnerabilities
4. Check for default credentials on demo environment
5. Assess NMS access controls

## Related Entities
- [[technovasolutions.io]]
- [[TechNova Solutions]]
- [[Intelligence Analysis - Digital Infrastructure]]
- [[Intelligence Analysis - Technology Stack]]

## Tags
#Infrastructure #Reconnaissance #OSINT #Subdomains #Hetzner #Germany #TechNova
