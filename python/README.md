# Memory usage script in Python

## Install 

1. Clone the repository:
```
git clone https://github.com/ASivashs/Memory_usage_scripts.git
```

2. Install the required dependencies:
```
pip3 install -r requirements.txt
```

3. Grant execution permission to the script:
```
chmod +x ./memory_control.py
```


## Usage

To run the script with default parameters (80% of memory usage and http://127.0.0.1:8080/reports as the request url), use the following command:
```
python3 memory_control.py
```

To specify a custom memory usage percentage and request URL, use the following command:
```
python3 memory_control.py -n [time between iterations] -m [memory usage percentage, e.g. 30, 40] -r [url]
```


## Help

For additional information and options, run the script with the following command:
```
python3 memory_control.py --help
```
