# HANSHIN-Tigers-report
It tells you HANSHIN Tigers (Japanese STRONG Baseball Team) report.

## Requirements
HANSHIN-Tigers-report requires the following to run:

- Python 3.4+

## Usage
Install python libraries:
```bash
$ pip install requests
$ pip install beautifulsoup4
$ pip install lxml
```

Clone software:
```bash
$ git clone https://github.com/donchan922/HANSHIN-Tigers-report.git
$ cd HANSHIN-Tigers-report
```

Modify software:
```bash
$ vi tigers_report.py

# replace YOUR-USER-AGENT to your User-Agent (e.g. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/64.0.3282.167 Safari/537.36)
headers = {'User-Agent': 'YOUR-USER-AGENT'}
```

Execute following command:
```bash
$ python tigers_report.py
```

result (for example):
```bash
試合終了
巨7 - 神2
```
Fight! Fight! HANSHIN Tigers!

## License
This software is released under the MIT License, see LICENSE.
