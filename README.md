### Usage:
```code
subdominator -h
```
```yaml
 _____________  __________ ________ _______ ______  __________ _____________   _________ _______________ ________ 
    __  ___/__  / / /___  __ )___  __ \__  __ \___   |/  /___    |____  _/___  | / /___    |___  __/__  __ \___  __ \ 
    _____ \ _  / / / __  __  |__  / / /_  / / /__  /|_/ / __  /| | __  /  __   |/ / __  /| |__  /   _  / / /__  /_/ /   [V1]
    ____/ / / /_/ /  _  /_/ / _  /_/ / / /_/ / _  /  / /  _  ___ |__/ /   _  /|  /  _  ___ |_  /    / /_/ / _  _, _/
    /____/  \____/   /_____/  /_____/  \____/  /_/  /_/   /_/  |_|/___/   /_/ |_/   /_/  |_|/_/     \____/  /_/ |_|

                                                                                                    - DHRUGESH M.J
usage: subdomainator.py [-h] -d DOMAIN -w WORDLIST [-t THREADS] [-o OUTPUT]

Subdomain Finder

options:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        Target domain (e.g., example.com)
  -w WORDLIST, --wordlist WORDLIST
                        Path to the wordlist file
  -t THREADS, --threads THREADS
                        Number of threads (default: 10)
  -o OUTPUT, --output OUTPUT
                        Output file to save the subdomains (default: subdomains.txt)
```
### Installation:

**Subdominator requires python latest version to be installed and with latest version `pip` commandline tool 
```code
git clone https://github.com/Dhurgesh-mj/Subdomainator.git
pip3 install -r requirements.txt ## not needed u can skip this step
python3 subdomainator.py -h
```
