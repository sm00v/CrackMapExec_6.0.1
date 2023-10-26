# CrackMapExec_6.0.1 Install from Zip

```
unzip v6.0.1.zip && 
cd CrackMapExec-6.0.1 &&
pip3 install -r requirements.txt --break-system-packages &&
pip3 install .

# Delete old cme data in case install won't run:
vim /var/lib/dpkg/status
rm /usr/lib/python3.11/EXTERNALLY-MANAGED
```
