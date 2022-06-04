# CVE-2021-25076-Exploit
### Wordpress Plugin WP User Frontend < 3.5.26 - SQL-Injection (Authenticated)

## CVE description:
The WP User Frontend WordPress plugin before 3.5.26 does not validate and escape the status parameter
before using it in a SQL statement in the Subscribers dashboard, leading to an SQL injection.
Due to the lack of sanitisation and escaping, this could also lead to Reflected Cross-Site Scripting
- https://nvd.nist.gov/vuln/detail/CVE-2021-25076

## ExploitDB:
- https://www.exploit-db.com/exploits/50772
  
## Exploit Description:
- Vendor Homepage: https://wedevs.com/
- Software Link: https://downloads.wordpress.org/plugin/wp-user-frontend.3.5.25.zip
- Version: Up to 3.5.25
- Tested on Ubuntu 20.04

- 🕊️ Twitter: [@0xAbbarhSF](https://twitter.com/0xAbbarhSF)
[![Tweet](https://img.shields.io/twitter/url/http/0xAbbarhSF.svg?style=social)](https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Fdeveloper.twitter.com%2Fen%2Fdocs%2Ftwitter-for-websites%2Ftweet-button%2Foverview&ref_src=twsrc%5Etfw&text=CMS-Xploiter%20-%20Automated%20Pentest%20Recon%20Scanner%20%400xAbbarhSD&tw_p=tweetbutton&url=https%3A%2F%2Fgithub.com%2F0xAbbarhSF%)

