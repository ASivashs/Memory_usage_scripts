# Memory usage script in Bash

## Install 

1. Clone the repository:
```
git clone https://github.com/ASivashs/Memory_usage_scripts.git
```
2. Grant execution permission to the script:
```
chmod +x ./memory_control.sh
```


## Dependencies

If curl not installed in your system install it with command:

Debian/Ubuntu
```
apt install curl
```
CentOS/Red Hat/Fedora
```
yum install curl
```


## Usage

To run the script with default parameters (80% of memory usage and http://127.0.0.1:8080/reports as the request url), use the following command:
```
./memory_control.sh
```

To specify the memory usage and request URL, use the following command:
```
./memory_control.sh [memory usage percentage, e.g. 30, 40] [url]
```

Run script in the background:
```
./memory_control.sh &
```
