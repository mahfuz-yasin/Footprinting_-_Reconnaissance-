# 🧭 Footprinting & Reconnaissance Commands Summary
| 🔢 Command                               | 📌 Purpose (ব্যবহার)                              | 🖥️ Where to Write (কোথায় লিখবেন)         | ⚙️ Tool Install/Requirement                    |
|-----------------------------------------|---------------------------------------------------|--------------------------------------------|-------------------------------------------------|
| `whois example.com`                     | ডোমেইন মালিকানা ও রেজিস্ট্রার তথ্য বের করতে     | Linux/Mac Terminal, WSL                    | `sudo apt install whois`                        |
| `dig example.com any`                   | DNS রেকর্ড সংগ্রহ করতে                            | Linux/Mac Terminal                         | `sudo apt install dnsutils`                     |
| `host -a example.com`                   | DNS বিস্তারিত তথ্য দেখতে                         | Linux/Mac Terminal                         | `sudo apt install dnsutils`                     |
| `theHarvester -d example.com -b google` | ইমেইল, ডোমেইন তথ্য গুগল থেকে সংগ্রহ             | Linux Terminal                             | `sudo apt install theharvester`                 |
| `exiftool document.pdf`                 | ডকুমেন্ট বা ছবির মেটাডেটা বের করতে              | Linux/Mac Terminal                         | `sudo apt install libimage-exiftool-perl`       |
| `nmap -sS -p- 192.168.0.1`              | সব পোর্ট স্ক্যান করতে                             | Linux Terminal                             | `sudo apt install nmap`                         |
| `nmap -O 192.168.0.1`                   | OS ফিংগারপ্রিন্ট করতে                             | Linux Terminal                             | `sudo apt install nmap`                         |
| `nc 192.168.0.1 80`                     | Banner Grabbing (Apache/Nginx শনাক্তকরণ)        | Linux Terminal                             | `sudo apt install netcat`                       |
| `traceroute example.com`               | রাউট বিশ্লেষণ করতে                               | Linux Terminal                             | `sudo apt install traceroute`                   |
| `sublist3r -d example.com`             | সাবডোমেইন এনুমারেশন করতে                        | Linux Terminal                             | `sudo apt install sublist3r`                    |
| `recon-ng`                              | Automated OSINT Framework চালাতে                 | Linux Terminal                             | `sudo apt install recon-ng` অথবা `git clone`    |
| `amass enum -d example.com`            | ডোমেইন, সাবডোমেইন খুঁজতে                         | Linux Terminal                             | `sudo snap install amass`                       |
| `dnstwist example.com`                 | Typosquatting ডোমেইন খুঁজতে                     | Linux Terminal                             | `pip install dnstwist`                          |
| `snmpwalk -v2c -c public 192.168.0.1`   | SNMP Enumeration                                  | Linux Terminal                             | `sudo apt install snmp`                         |
