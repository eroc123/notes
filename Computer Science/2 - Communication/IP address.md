
https://www.youtube.com/watch?v=5o8CwafCxnU

Unique assigned identifier for each and every device on the internet

IP : internet protocol

### IPv4
4 $\times$ 8 bit numbers, separated by a period ".", for a total of 32 bits
e.g. 127.0.0.1

An IP address usually are laid out like below 

| 174 | 129 |  14 | 120 |
| --- | --- | --- | --- |
|Country|Region|Subnetwork|Device|


### IPv6
New standard for IP addresses, as IPv4 only supports around 4 billion unique addresses, IPv6 increases the limit to allow increased unique devices

8 $\times$ 4 hex digits, for a total 128 bits, separated by a colon ":"
e.g. 3FFE:F200:0234:AB00:0123:4567:8901:ABCD

### How IP work

A computer visiting a website sends a message containing the website's IP address, as well as its own IP address. Including its own IP address allows the server to know where to send the response to.

<<<<<<< HEAD
#### DNS


Computer use DNS to look up domain name (part of the [[URL]])

DNS stands for Domain Name Server, they are responsible for translating domain names to IP addresses. 

DNS are laid out in a hierarchy 

Frist the computer would ask the local DNS for the IP address, if the local DNS does not have the IP address in its cache, it will ask a higher level DNS. This repeats until either the URL is found (with the top level DNS or other lower level DNS), or an address not found error is returned

##### This note discusses (IP address and DNS server) the process by which a computer looks for the web server requested, the note that discusses what happens after a web server is found is [[HTTP and HTML (web browsing)]]
=======
>>>>>>> origin/main
