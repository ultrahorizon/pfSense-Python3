# pfSense Python 3


## Overview

It's a well known fact that at present pfSense only comes shipped with Python 2.7. As Python 2.7 is due to be deprecated on the 1st January 2020, this repository aims to provide an easy and quick way to install Python 3 on pfSense. A variety of Python 3 versions are available for each pfSense revision. These will be updated as pfSense stable releases are created.

## Easy Installation

Follow these steps to install a particular Python 3 version on your pfSense machine.

1. SSH into your pfSense machine and bring up a shell prompt.
2. Ensure git is installed:

```sh
$> pkg install git
``` 

3. Clone this repository:

```sh
$> cd /tmp
$> git clone git@github.com:ultrahorizon/pfSense-Python3.git
``` 

4. Enter the appropriate pfSense version directory:

```sh
$> cd /pfSense-Python3/<PFSENSE_VERSION>
``` 

For example, pfSense 2.4.4 would be:

```sh
$> cd /pfSense-Python3/2.4.4
```

5. List available Python 3 binaries:

```sh
$> ls
```

6. Install the appropriate Python 3 version for your requirements:

```sh
$> pkg add <PYTHON_TXZ_FILE>
```

For example, Python 3.8 would be:

```sh
$> pkg add 3.8.txz
```