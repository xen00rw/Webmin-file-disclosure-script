# Webmin File Disclosure Exploit (CVE 2006-3392)

![created](https://img.shields.io/badge/platform-linux-blue)
![language](https://img.shields.io/badge/language-python-blue)
[![Twitter](https://aleen42.github.io/badges/src/twitter.svg)](https://twitter.com/willxenoo)


First off all, Hello guys 

I've created this tool to pratice about automating my own tasks and training programming languages.
This is an simple exploit to explore a vuln that exists in Webmin. (Webmin < 1.290 / Usermin < 1.220 - Arbitrary File Disclosure - CVE 2006-3392)

First of all you'll need requests installed to use the script.

## Requirements
Use the package manager to install de requirements.

```bash
$ pip install requirements.txt
```
## Usage

```bash
$ python3 exploit.py -r 192.168.0.1 -x 10000 -y HTTP -z /etc/passwd

-r = hostname or ip address 
-x = port of webmin service (Default: 10000)
-y = protocol of the host (Default: HTTP)
-z = file to download from the host (Default: /etc/passwd)
```

## P.S.

It's not too complex to use, but it'll help you automating and getting files easier from the server.

I hope it helps.

Thanks !!<

From you Friend, Xen00rw

## References

https://nvd.nist.gov/vuln/detail/CVE-2006-3392

https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2006-3392

https://www.cvedetails.com/cve/CVE-2006-3392/

