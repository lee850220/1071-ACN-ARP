# 107ACN-ARP
ARP packet capture, modify, and send.


## Usage
```
1) ./arp -l -a
2) ./arp -l <filter_ip_address>
3) ./arp -q <query_ip_address>
4) ./arp <fake_mac_address> <target_ip_address>
5) ./arp <fake_mac_address> <target_ip_address> -t
6) ./arp <fake_mac_address> <target_ip_address> <attack_ip_address>
```
**Note**

Please check your Network Card Interface ID, and use "```make test DEVICE=<your interface ID>```" to compile.
        In default settings, use "```make```" is "**enp2s0f5**", and use "```make test```" is "**ens33**".
- - -

## ChangeLog
Ver 1.0
ARP sniffer & spoof program with 4 command and 1 help command.
```
1) ./arp -l -a
2) ./arp -l <filter_ip_address>
3) ./arp -q <query_ip_address>
4) ./arp <fake_mac_address> <target_ip_address>
```
Ver 1.1
Add new command for looping spoof in command 4 with flag "-t".

Ver 1.2
Protable to Windows_NT system. (not working)

Ver 1.3
Add new command for looping spoof to specific target IP to attack.

I.E. 
```
./arp <fake_mac_address> <target_ip_address> <attack_ip_address>
```

- - -

## ScreenShot
![](https://github.com/lee850220/1071-ACN-ARP/blob/main/spoof%20looping.png)

- - -

