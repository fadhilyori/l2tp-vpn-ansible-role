# L2TP VPN Installer

Author: Fadhil Yori Hibatullah <fadhil4812@gmail.com>

# Requirements
1. Python3

# How to Use : 
1. Create python3 virtualenv (optional)
```
virtualenv -p python3 venv
```
2. Source python3 virtual env
```
source venv/bin/activate
```
3. Install ansible using this script
```
pip install -r requirements.txt
```
5. Change variable at vars/main.yml
6. Create a new file named hosts based on example-host file
7. Run this script to deploy
```
ansible-playbook -K -i hosts main.yml
```

# License
MIT