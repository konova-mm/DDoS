## Tools And Scripts for DDoS Testing

### Hping
``It makes the DDoS attack by sending TCP/IP, UDP, ICMP, SYN packets. It displays the replies similar to Ping program. This tool is created for testing purposes. It is used for testing firewall rules.``
#### [Download](www.hping.org)

### Nemesy
`` Nemesy is a denial of service attack tool which generates random packets with spoofed IP addresses. Run on Windows 2000/XP/NT.``
#### [Download](https://packetstormsecurity.com/files/25599/nemesy13.zip.html)

### HULK
``HULK stands for HTTP Unbearable Load King. It is a DoS attack tool for the web server. It is created for research purposes.

Features:

    It can bypass the cache engine.
    It can generate unique and obscure traffic.
    It generates a great volume of traffic at the web server.

Verdict: It may fail in hiding the identity. Traffic coming through HULK can be blocked.``
#### [Download](https://packetstormsecurity.com/files/112856/HULK-Http-Unbearable-Load-King.html)


### Tor’s Hammer
``This tool is created for testing purposes. It is for slow post attack.

Features:

    If you run it through Tor network then you will remain unidentified.
    In order to run it through Tor, use 127.0.0.1:9050.
    With this tool, the attack can be made on Apache and IIS servers.

Verdict: Running the tool through the Tor network will have an added advantage as it hides your identity.``
#### [Download](https://sourceforge.net/projects/torshammer/)

### Slowloris
``Slowloris tool is used to make a DDoS attack. It is used to make the server down.

Features:

    It sends authorized HTTP traffic to the server.
    It doesn’t affect other services and ports on the target network.
    This attack tries to keep the maximum connection engaged with those that are open.
    It achieves this by sending a partial request.
    It tries to hold the connections as long as possible.
    As the server keeps the false connection open, this will overflow the connection pool and will deny the request to the true connections.

Verdict: As it makes the attack at a slow rate, traffic can be easily detected as abnormal and can be blocked.``
#### [Download](https://github.com/gkbrk/slowloris)


### LOIC
``LOIC stands for Low Orbit Ion Cannon. It is a free and popular tool that is available for the DDoS attack.

Features:

    It is easy to use.
    It sends UDP, TCP, and HTTP requests to the server.
    It can do the attack based on the URL or IP address of the server.
    Within seconds, the website will be down and it will stop responding to the actual requests.
    It will NOT HIDE your IP address. Even using the proxy server will not work. Because in that case, it will make the proxy server a target.

Verdict: HIVEMIND mode will allow you to control remote LOIC systems. With the help of this, you can control the other computers in the Zombie network.``
#### [Donwload](https://sourceforge.net/projects/loic/)

### XOIC
``It is a DDoS attacking tool. With the help of this tool, the attack can be made on small websites.

Features:

    It is easy to use.
    It provides three modes to attack.
        Testing mode.
        Normal DoS attack mode.
        DoS attack with TCP or HTTP or UDP or ICMP message.

Verdict: Attack made using XOIC can be easily detected and blocked.``
#### [Download](https://sourceforge.net/directory/?q=xoic)

### Ddosim
``DDOSIM stands for DDoS Simulator. This tool is for simulating the real DDoS attack. It can attack on the website as well as on the network.

Features:

    It attacks the server by reproducing many Zombie hosts.
    These hosts create a complete TCP connection with the server.
    It can do HTTP DDoS attack using valid requests.
    It can do DDoS attack using invalid requests.
    It can make an attack on the application layer.

Verdict: This tool works on Linux systems. It can attack with valid and invalid requests.``
#### [Download](https://sourceforge.net/projects/ddosim/)

### Pyloris
``This tool is created for testing. To make a DoS attack on the server, this tool uses SOCKS proxies and SSL connections.

Features:

    The attack can be made on HTTP, FTP, SMTP, IMAP, and Telnet.
    It has an easy to use GUI.
    It directly makes an attack on service.

Verdict: It has python dependency and installation also can be difficult. It can make attacks on various protocols.``
#### [Download](https://sourceforge.net/projects/pyloris/)

### OWASP DOS HTTP POST:
``OWASP stands for Open Web Application Security Project. This tool is created for testing against the application layer attacks. It can also be used to test the performance. This tool can be used to decide the capacity of the server.``
#### [Download](https://www.owasp.org/index.php/OWASP_HTTP_Post_Tool)

### Thc-ssl-dos:
``This attack uses the SSL exhaustion method. It makes the server down by exhausting all the SSL connections. It can work using a single machine.``
#### [Download](https://github.com/azet/thc-tls-dos)

