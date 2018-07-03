# Python_TCP_DDoS_Script
Python-Based DDoS Script to Flood a Web Server with Requests

# Installing Dependencies Ubuntu
```
sudo apt-get update && sudo apt-get -y upgrade
sudo apt-get install -y python3-pip
sudo apt-get install build-essential libssl-dev libffi-dev python-dev
python3 -V
```

# Installing Dependencies CentOS7
```
sudo yum install -y https://centos7.iuscommunity.org/ius-release.rpm
sudo yum update
sudo yum install -y python36u python36u-libs python36u-devel python36u-pip
sudo yum groupinstall -y "Development Tools"
python3.6 -V
```

# Installing The Script
```
cd /
mkdir DDoS
cd DDoS
git clone https://github.com/RoqueNight/Python_TCP_DDoS_Script.git
cd Python_TCP_DDoS_Script
chmod +x TCPDeface.py
python3 TCPDeface.py -s <IP> -t 100
```


