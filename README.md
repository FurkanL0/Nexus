# Nexus Node Setup

![image](https://github.com/user-attachments/assets/ca6aff98-5366-4775-8d69-7334fc390765)

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 9++ GB                     |
| **Storage**      | 50 GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

# Web / Sing Up : 

-  https://app.nexus.xyz/ - Register on the site with your wallet and email at the top right - it's better to use the same one you used on the old testnet.

## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

```bash
sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler
```


```bash
sudo apt remove -y protobuf-compiler
sudo curl -LO https://github.com/protocolbuffers/protobuf/releases/download/v21.12/protoc-21.12-linux-x86_64.zip
sudo apt install unzip
sudo unzip protoc-21.12-linux-x86_64.zip -d /usr/local
sudo chmod +x /usr/local/bin/protoc
rm protoc-21.12-linux-x86_64.zip
```

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```bash
source $HOME/.cargo/env
```

# 3. Nexus CLI : 

```bash
screen -S nexus
```

```bash
curl https://cli.nexus.xyz/ | sh
```
![image](https://github.com/user-attachments/assets/36587c62-f46f-4625-8310-414457aa4186)

![image](https://github.com/user-attachments/assets/53fc86b1-6c86-4d70-8716-60095f645419)

![image](https://github.com/user-attachments/assets/656f0c05-d5d3-4c9e-a542-97d349d87ef0)


![image](https://github.com/user-attachments/assets/dbba1476-b2d2-4710-929e-d014582cb19a)

## Fist 2 and Enter your ID.


## Web : 

![image](https://github.com/user-attachments/assets/711cde21-4716-4850-a901-558f79071196)

- Link : https://app.nexus.xyz/
