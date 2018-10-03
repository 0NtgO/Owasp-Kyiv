# Owasp Kyiv: Burp Suite Workshop

## Presentation
* [Burp Suite - from First Run to Website Hack in 60 min ](https://github.com/0NtgO/Owasp-Kyiv/blob/master/Owasp_Kiev_29.09.pdf)

## Labs
## Description of tasks 
* Task 1 - Basic Login Form <details><summary>What should be done</summary>1. Find valid username 
  2.  Find valid password</details>
* Task 2 - HTTP Basic Authentication <details><summary>What should be done</summary>Find vald username and password</details>
* Task 3 - Login Form with one time token <details><summary>What should be done</summary>1. Find valid username 
  2.  Find valid password</details>
* Task 4 - LFI <details><summary>What should be done</summary>1. Find valid username 
  2.  Find valid password 3. Exploit LFI with LFISuite</details>
* Task 5 - Reflected XSS <details><summary>What should be done</summary>Exploit XSS with XSShunter</details>
* Task 6 - Reflected XSS with one time token <details><summary>What should be done</summary>Exploit XSS with XSShunter</details>
* Task 7 - Stored XSS on another page <details><summary>What should be done</summary>Exploit XSS with XSShunter and create macros to open comment page</details>
* Task 8 - LFI + Automatic Logout every 5 seconds <details><summary>What should be done</summary>1. Find valid username 
  2.  Find valid password 3. Exploit LFI with LFISuite 4. Create macros to autologin</details>

### Docker Hub
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_1/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_2/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_3/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_4/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_5/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_6/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_7/
* https://hub.docker.com/r/j0ns1k/owasp_kyiv_task_8/
### How to run
* Install docker
* docker pull j0ns1k/owasp_kyiv_task_1 (docker pull j0ns1k/owasp_kyiv_task_{1-8}) from 1 to 8
* docker run -p 81:80 -td j0ns1k/owasp_kyiv_task_1 (docker run -p 8{1-8}:80 -td j0ns1k/owasp_kyiv_task_{1-8} ) 

## Labs online 
* http://173.212.213.238:81
* http://173.212.213.238:82
* http://173.212.213.238:83
* http://173.212.213.238:84
* http://173.212.213.238:85
* http://173.212.213.238:86
* http://173.212.213.238:88
* http://173.212.213.238:89
