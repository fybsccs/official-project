

<h1 style="color:red">#Unix/Linux Enumeration</h1>

**Enumeration** is defined as the process of extracting user names, machine names,
network resources, shares and services from a system. In this phase, the
attacker creates an active connection to the system and performs directed
queries to gain more information about the target.

The gathered information is used to identify the vulnerabilities or weak points
in system security and tries to exploit in the System gaining phase.

UNIX or Linux Operating System can be enumerated with multiple command line
utilities provided by the OS. Below is the list of utilities.

> Rpcclient

> rpcinfo

> finger

> showmount

> enum4linux

> linux smart enumeration (used in this experiment)

<h2>POC:</h2>

1.Scan for running services and Operating System using nmap

![](https://raw.githubusercontent.com/fybsccs/official-project/master/nmapos.png)

2.Scan for vulnerable services

![](https://raw.githubusercontent.com/fybsccs/official-project/master/services.png)

3.Exploit the services
![](https://raw.githubusercontent.com/fybsccs/official-project/master/nc.png)

4.Use tools like enum4linux or lse to extract information about the system

![](https://raw.githubusercontent.com/fybsccs/official-project/master/exploit.png)