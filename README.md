# Linux-Privilege-Escalation-CheatSheet

## Commands for Linux Privilege Escalation
1. https://gtfobins.github.io/
2. For finding SUID: `find / -perm -u=s -type f 2>/dev/null`

## Tools to identify weakness
1. [LinPeas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS)
2. [LinEnum](https://github.com/rebootuser/LinEnum)
3. [Linux Exploit Suggester](https://github.com/mzet-/linux-exploit-suggester)
4. [Linux Priv Checker](https://github.com/sleventyeleven/linuxprivchecker)

## Exploits
1. [Kernel Exploits](https://github.com/lucyoa/kernel-exploits)

## Escalation Path: Capabilities
1. `getcap -r / 2>/dev/null`
   - If it has `cap_setuuid+ep` present

## Resources
1. [Linux Privilege Escalation](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md)

# Examples: 
1. wget example - https://veteransec.com/2018/09/29/hack-the-box-sunday-walkthrough/
