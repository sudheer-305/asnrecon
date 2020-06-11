# ASNRECON
[![License: Apache](https://img.shields.io/github/license/orlyjamie/asnrecon)](https://img.shields.io/github/license/orlyjamie/asnrecon)

A tool to perform reconaissance using autonomous system number (ASN) lookups combined with SSL cert scanning 📡

![](https://raw.githubusercontent.com/orlyjamie/asnrecon/master/screen.png)

## Usage

```
usage: python asnrecon.py

Select an option:
	[1] Full ASN scan
	[2] Specific IPv4 range scan
1
Please input the host name: office.com
File "main.config" is missing, ips will not be ignored.
Found ranges ['104.44.65.0/24', '104.44.66.0/24', '104.44.67.0/24', '104.44.70.0/24', '104.44.73.0/24', '104.44.75.0/24', '104.44.77.0/24', '13.107.12.0/24', '13.107.128.0/24', '13.107.129.0/24', '13.107.13.0/24', '13.107.136.0/24', '13.107.137.0/24', '13.107.140.0/24', '13.107.15.0/24', '13.107.16.0/24', '13.107.160.0/24', '13.107.18.0/24', '13.107.19.0/24', '13.107.198.0/24', '13.107.202.0/24', '13.107.204.0/24', '13.107.208.0/24', '13.107.21.0/24', '13.107.219.0/24', '13.107.22.0/24', '13.107.220.0/24', '13.107.221.0/24', '13.107.24.0/24', '13.107.246.0/24', '13.107.253.0/24', '13.107.254.0/24', '13.107.3.0/24', '13.107.39.0/24', '13.107.4.0/24', '13.107.40.0/24', '13.107.42.0/24', '13.107.43.0/24', '13.107.44.0/24', '13.107.46.0/24', '13.107.47.0/24', '13.107.48.0/24', '13.107.49.0/24', '13.107.5.0/24', '13.107.50.0/24', '13.107.51.0/24', '13.107.52.0/24', '13.107.53.0/24', '13.107.54.0/24', '13.107.56.0/24', '13.107.58.0/24', '13.107.6.0/24', '13.107.7.0/24', '13.107.9.0/24', '131.253.21.0/24', '131.253.3.0/24', '131.253.33.0/24', '150.171.32.0/24', '150.171.40.0/24', '150.171.41.0/24', '150.171.44.0/24', '198.180.74.0/24', '198.180.75.0/24', '204.14.180.0/24', '204.79.197.0/24', '40.66.93.0/24', '40.90.4.0/24', '52.113.194.0/24', '52.113.195.0/24', '52.113.196.0/24', '52.113.197.0/24', '64.4.48.0/24', '65.54.193.0/24', '65.54.196.0/24', '65.54.198.0/24', '65.54.199.0/24', '65.54.200.0/24', '65.54.202.0/24', '65.54.203.0/24', '65.54.205.0/24', '65.54.207.0/24', '65.54.208.0/24', '65.54.211.0/24', '65.54.214.0/24', '65.54.215.0/24', '65.54.216.0/24', '65.54.219.0/24', '65.54.222.0/24', '94.245.84.0/24']
Testing 104.44.65.0/24...

```

## Installation
  1. `pip install -r requirements.txt`
  2. `wget https://raw.githubusercontent.com/hadiasghari/pyasn/master/pyasn-utils/pyasn_util_download.py`
  3. `wget https://raw.githubusercontent.com/hadiasghari/pyasn/master/pyasn-utils/pyasn_util_convert.py`
  4. `python pyasn_util_download.py --latest`
  5. `python pyasn_util_convert.py --single RIBFILE rib.dat`
  
  Alternatively just run the installer (installer.sh)
  `sh install.sh`
