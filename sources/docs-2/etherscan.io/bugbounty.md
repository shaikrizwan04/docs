# Source: https://etherscan.io/bugbounty

# Bug Bounty Program

1. ### Guidelines

 We ask that all researchers:

 - Make every effort to avoid privacy violations, degradation of user experience, disruption to production systems, and destruction of data during security testing
 - Use the identified communication channels to report vulnerability information to us
 - Report vulnerabilities as soon as you discover it, but keep it confidential between yourself and Etherscan until we’ve resolve the issue
 - Provide us with at least 7 working days to investigate the issue and revert back to you
2. ### If you are the first to report the issue, and we make a code or configuration change based on the issue, we commit to:

 - Recognize your contribution on Etherscan.io (list below for the last 50 contributors)
 - Reward you with a bounty (up to a maximum of $3000 paid out per month):
 1. $1000-$3000 in crypto equivalent if you identified a vulnerability that presented a critical risk \*
 2. $500 in crypto equivalent if you identified a vulnerability that presented a high risk \*
 3. $250 in crypto equivalent if you identified a vulnerability that presented a moderate risk \*
 4. $0 in crypto equivalent if you identified a vulnerability that presented a low risk \*
 5. Entry in Hall of Fame Only, If there was in fact no or low risk vulnerability, but we still made a code or configuration change nonetheless

 _Researcher will provide us with a wallet address based on the reported explorer for the payout within 7 days after we have resolved the issue._ 
 _\* vulnerability level will be determined at our discretion_ 
 _\*\* in the event the vulnerabilty exists in multiple explorers, only the reported explorer is entitled to the rewards_ 

3. ### Scope

 Etherscan (etherscan.io) and explorers under EaaS ([https://etherscan.io/explorer-as-a-service-eaas](https://etherscan.io/explorer-as-a-service-eaas)) 

 We are interested in the following vulnerabilities:

 - Business logic issues
 - Remote code execution (RCE)
 - Database vulnerability, SQLi
 - File inclusions (Local & Remote)
 - Access Control Issues (IDOR, Privilege Escalation, etc)
 - Leakage of sensitive information
 - Server-Side Request Forgery (SSRF)
 - Other vulnerability with a clear potential loss
4. ### Out of scope

 Subsequent reports from the same researcher describing a bypass or variant of their previously reported vulnerability (e.g. incomplete fix, same root cause) will be treated as part of the original submission and are not eligible for a separate reward

 Vulnerabilities found in out of scope resources are unlikely to be rewarded unless they present a serious business risk (at our sole discretion). In general, the following vulnerabilities do not correspond to the severity threshold

 - Visual typos, spelling mistakes, etc
 - Findings derived primarily from social engineering (e.g. phishing, etc)
 - Findings from applications or systems not listed in the ‘Scope’ section
 - UI/UX bugs, Data entry errors, spelling mistakes, typos, etc
 - Network level Denial of Service (DoS/DDoS) vulnerabilities
 - Certificates/TLS/SSL related issues
 - DNS issues (i.e. MX records, SPF records, etc.)
 - Server configuration issues (i.e., open ports, TLS, etc.)
 - Spam or Social Engineering techniques
 - Security bugs in third-party applications or services
 - XSS Exploits that do not pose a security risk to 'other' users (Self-XSS)
 - Login/Logout CSRF-XSS
 - https/ssl or server-info disclosure related issues
 - https Mixed Content Scripts
 - Brute Force attacks
 - Best practices concerns
 - Recently (less than 30 days) disclosed 0day vulnerabilities
 - Username/email enumeration via Login/Forgot Password Page error messages
 - Missing HTTP security headers
 - Weak password policy
 - HTML injection
5. ### How to Report a Security Vulnerability

 - Description of the location and potential impact of the vulnerability
 - A detailed description of the steps required to reproduce the vulnerability (POC scripts, screenshots, and compressed screen captures are all helpful to us)
 - Your name/handle and a link for recognition in our Hall of Fame (twitter, reddit, facebook, hackerone, etc)
 - List down the affected explorer(s)
 - Email us at [\[Bug Bounty Report\]](mailto:bugbounty@EtherScan.io?subject=BugBounty)

---

### HALL OF FAME

Special thanks to the following researchers for helping us make Etherscan and other explorers a better place

- Harshil Nayi - [https://www.linkedin.com/in/harshilnayi/](https://www.linkedin.com/in/harshilnayi/)
- zaiko - [https://t.me/zaikofufu1](https://t.me/zaikofufu1)
- Viacheslav Dmitriev - [https://x.com/SovaSlavaDev](https://x.com/SovaSlavaDev)
- Jaysec - [https://github.com/jay111-bit](https://github.com/jay111-bit)
- Alex Wong - [https://hackerone.com/exploitstrikeops](https://hackerone.com/exploitstrikeops)
- AMJ - [https://x.com/AMJ87R8](https://x.com/AMJ87R8)
- Mrjanis - [https://hackerone.com/mrjanis](https://hackerone.com/mrjanis)
- Sajan Ghimire - [https://x.com/@QuietEcho18](https://x.com/@QuietEcho18)
- Uxío Fuentefría
- Smile Kamboj - [https://www.linkedin.com/in/smile-and-exploit-234711321/](https://www.linkedin.com/in/smile-and-exploit-234711321/)
- Brahim Ghazi - [https://www.linkedin.com/in/brahim-g-15577725a](https://www.linkedin.com/in/brahim-g-15577725a)
- Maneesha Dewmina (DM4N) - [https://www.linkedin.com/in/maneesha-dewmina/](https://www.linkedin.com/in/maneesha-dewmina/)
- Muhammad Nur - [https://www.linkedin.com/in/muhammadnur-id/](https://www.linkedin.com/in/muhammadnur-id/)
- Alex - [https://x.com/d0rsky](https://x.com/d0rsky)
- AyushXtha - [https://hackerone.com/ayushxtha](https://hackerone.com/ayushxtha)
- Uwin - [https://x.com/0xuwin](https://x.com/0xuwin)
- Peilin Zheng - [https://x.com/tczpl\_](https://x.com/tczpl_)
- Yadnesh Chavhan - [https://www.linkedin.com/in/yadnesh-chavhan-9981a42a3](https://www.linkedin.com/in/yadnesh-chavhan-9981a42a3)
- Sattyam - [https://x.com/0xDefult](https://x.com/0xDefult)
- 0daystolive - [https://sorcery.ie](https://sorcery.ie)
- Ma Pengxiang - [https://x.com/MaLucasBC](https://x.com/MaLucasBC)
- n9h3ch0\_2935 - [https://hackerone.com/n9h3ch0\_2935](https://hackerone.com/n9h3ch0_2935)
- Jonas Dias Rebelo - [https://www.linkedin.com/in/jonasdiasrebelo/](https://www.linkedin.com/in/jonasdiasrebelo/)
- Yushi - [https://x.com/abmushi](https://x.com/abmushi)
- Jeff McDonald - [https://github.com/jabo38](https://github.com/jabo38)
- Henrique Scocco - [https://www.linkedin.com/in/henrique-scocco-030618171/](https://www.linkedin.com/in/henrique-scocco-030618171/)
- SamCzun - [https://twitter.com/samczsun](https://twitter.com/samczsun)
- Martin Abbatemarco - [https://hackingmood.com](https://hackingmood.com)
- Andrew Curtin - [https://www.twitter.com/adcurtin](https://www.twitter.com/adcurtin)
- Shivam Kamboj Dattana - [https://www.twitter.com/Sechunt3r](https://www.twitter.com/Sechunt3r)
- David Fiala - [https://www.fiala.me/](https://www.fiala.me/)
- Raz0r of Positive.com
- Yaroslav Babin - [https://positive.com](https://positive.com)
- Taha Smily - [https://twitter.com/TahakhanTaha](https://twitter.com/TahakhanTaha)
- Ahsankhan
- Sai Naik - [http://hackingmonks.net](http://hackingmonks.net)
- Anas Roubi
- Sumit Sahoo - [https://www.sumitsahoo.com/](https://www.sumitsahoo.com/)
- Swaroop Yermalkar - @swaroopsy
- Mohd Aqeel Ahmed (Ciph3r00t) - [https://www.facebook.com/ciph3r00t](https://www.facebook.com/ciph3r00t)
- Muhamad Zeeshan - [fb.com/zeeshan.1338](https://fb.com/zeeshan.1338)
- Smit Gajra
- Shawar Khan - [https://shawarkhan.com](https://shawarkhan.com)
- Taimoor Abid - [https://www.facebook.com/T4YM.H4X0R](https://www.facebook.com/T4YM.H4X0R)
- Cristian Joseph D. Legacion - [https://www.facebook.com/cj.legacion10](https://www.facebook.com/cj.legacion10)
- Muhammad Zeeshan - [https://hackerone.com/zee\_shan](https://hackerone.com/zee_shan)
- Tayyab Qadir - [https://www.facebook.com/tqMr.EditOr](https://www.facebook.com/tqMr.EditOr)
- Arbin Godar - [www.arbingodar.com](http://www.arbingodar.com)
- Nirmal Thapa - [https://twitter.com/nirmal\_4n\_](https://twitter.com/nirmal_4n_)
- Sami Drif - [https://www.facebook.com/SaMi.Chichirovo](https://www.facebook.com/SaMi.Chichirovo)
- Hasan Bilen - [https://www.facebook.com/profile.php?id=1818527281](https://www.facebook.com/profile.php?id=1818527281)
- Vrde - [https://twitter.com/vrde](https://twitter.com/vrde)
- Roman Storm - [https://twitter.com/rstormsf](https://twitter.com/rstormsf)
- Mehedi Hasan - [https://www.facebook.com/polapaine.1337](https://www.facebook.com/polapaine.1337)
- Ngoc Chanh (J2TeaM) - [https://www.facebook.com/100002460766649](https://www.facebook.com/100002460766649)
- Hasan Khan - [https://www.facebook.com/profile.php?id=100028535957291](https://www.facebook.com/profile.php?id=100028535957291)
- Khan Janny - [https://twitter.com/reboot\_ex](https://twitter.com/reboot_ex)
- Joey Santoro - [https://twitter.com/joey\_\_santoro](https://twitter.com/joey__santoro)
- Kelvin Fitcher - [https://twitter.com/kelvinfichter](https://twitter.com/kelvinfichter)
- Dominik Opyd - [https://twitter.com/ririenei](https://twitter.com/ririenei)
- Samuel Curry - [https://twitter.com/PalisadeLLC](https://twitter.com/PalisadeLLC)
- Arseniy Reutov - [https://twitter.com/theRaz0r](https://twitter.com/theRaz0r)
- Gary Jones - [https://github.com/piratemoo](https://github.com/piratemoo)
- Shifty0g - [https://twitter.com/shifty0g](https://twitter.com/shifty0g)
- Ehsan Montahaei - [https://twitter.com/IAmS4n](https://twitter.com/IAmS4n)
- Rene - [https://twitter.com/renniepak](https://twitter.com/renniepak)
- Alexandru - [https://4websecurity.com](https://4websecurity.com)
- Nico Escalante
- Dylan Butler - [https://twitter.com/blankey1337](https://twitter.com/blankey1337)
- Sudip Roy - [https://twitter.com/0xsudip](https://twitter.com/0xsudip)
- lcfr.eth - [https://twitter.com/lcfr\_eth](https://twitter.com/lcfr_eth)
- Matan Berson - [https://hackerone.com/matanber](https://hackerone.com/matanber)