A curated collection of highly targeted, lightweight, and manually generated wordlists optimized for bug bounty hunting, reconnaissance, and security assessments. 

These wordlists are built to minimize noise, maximize efficiency, and cover critical discovery phases during security operations.

## 📁 Repository Structure & Contents

| File Name | Description | Use Case |
| :--- | :--- | :--- |
| `countries.txt` | Clean list of country names, codes, and variations. | Targeted targeting, parameter fuzzing, and localization testing. |
| `dnsgen-wordlist.txt` | Custom wordlist optimized for DNS alteration and permutation generation. | Discovering hidden subdomains via mass DNS resolution. |
| `domain-email-usernames.txt` | Targeted patterns combining corporate domains and common email/username structures. | Account enumeration, OSINT, and authentication testing. |
| `infrawords.txt` | Infrastructure-specific keywords (e.g., cloud providers, internal naming conventions, CI/CD). | Identifying shadow IT, exposed buckets, and staging environments. |
| `regions.txt` | Regional identifiers, state codes, and location-based naming conventions. | API endpoint fuzzing and region-restricted asset discovery. |
| `tld-mini.txt` | A high-probability list of Top-Level Domains (TLDs). | Fast multi-TLD expansion for brand monitoring and apex domain discovery. |
| `usernames.txt` | Clean, common administrative and application-level usernames. | Brute-forcing management interfaces and initial access vectors. |

## 🚀 Usage

These files are designed to be lightweight enough to plug directly into your daily automation pipelines and security tools.
