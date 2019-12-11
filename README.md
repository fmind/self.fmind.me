# self.fmind.me

## Setup

```bash
apt update && apt upgrade -y && apt install -y python
useradd myuser -m -G sudo -s /bin/bash
passwd myuser
```

## Access

```bash
mv /root/.ssh /home/myuser
chown -R myuser:myuser /home/myuser
```
