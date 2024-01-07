# Dynamic DNS Client for SAKURA

## Requirements

- curl
- nodejs
- json
- bash

## Installation

1. Get [node](https://nodejs.org).

*Note: Ubuntu users can install this command.*
```bash
apt install nodejs npm
```

2. Get [json](https://github.com/trentm/json/).

*Normal install command is*
```bash
npm install -g json
```

3. Check exists `curl` command.

```bash
which curl
```

**NOT responsed**

```bash
apt install curl
```

4. github clone

```bash
git clone https://github.com/e-frontier-systems/ddns_sakura.git
cd ./ddns_sakura
chmod +x ddns_sakura
```

5. Setting-up & Initialize

```bash
./ddns_sakura
```

6. Cron setting

```bash
sudo vi /etc/cron.d/ddns_sakura
```

```text
SHELL=/bin/bash
* * * * * root /path/to/ddns_sakura
```
