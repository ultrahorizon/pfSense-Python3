# pfSense Python 3


## Overview

Prior to version 2.4.5, pfSense only shipped with Python 2.7. This repository aims to provide a quick and easy way to install Python 3 on pfSense versions prior to 2.4.5. A variety of Python 3 versions are available for each pfSense revision. These will be updated as pfSense stable releases are created.

## Easy Installation (Python 3.6 on pfSense 2.4.4-RELEASE-p3 amd64)

1. SSH into your pfSense machine and bring up a shell prompt.
2. Download and install your required version of Python 3 (replace pfSense version and Python version as appropriate).
```sh
$> cd /tmp
$> fetch https://github.com/ultrahorizon/pfSense-Python3/raw/master/2.4.4-RELEASE-p3/amd64/3.6.txz
$> pkg add 3.6.txz
``` 

## Advanced Installation via Git (Python 3.6 on pfSense 2.4.4-RELEASE-p3 amd64)

Follow these steps to install Python 3.6 on your pfSense 2.4.4-RELEASE-p3 machine. Where applicable the steps below can be changed to suit different versions of Python or pfSense.

1. SSH into your pfSense machine and bring up a shell prompt.
2. Ensure git is installed:
```sh
$> pkg install git
``` 

3. Clone this repository to a directory of your choice:
```sh
$> git clone git@github.com:ultrahorizon/pfSense-Python3.git
``` 

4. Enter the appropriate pfSense version directory (in this case 2.4.4):
```sh
$> cd /pfSense-Python3/2.4.4-RELEASE-p3/amd64
``` 

5. Install the appropriate Python 3 version for your requirements (in this case Python 3.6):
```sh
$> pkg add 3.6.txz
```
