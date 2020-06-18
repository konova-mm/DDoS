 ## What is DoS Attack?

``` DOS is an attack used to deny legitimate users access to a resource such as accessing a website, network, emails, etc. or making it extremely slow. DoS is the acronym for Denial of Service. This type of attack is usually implemented by hitting the target resource such as a web server with too many requests at the same time. This results in the server failing to respond to all the requests. The effect of this can either be crashing the servers or slowing them down. ```

#### DoS 
This type of attack is performed by a single host
#### Distributed DoS
This type of attack is performed by a number of compromised machines that all target the same victim. It floods the network with data packets.

### 3 types of DDoS Attacks:

1. Volume-based attacks
2. Protocol attacks
3. Application layer attacks. ``
 
### Methods of doing DDoS attacks:

#### SYN Flood
``SYN Flood exploits weaknesses in the TCP connection sequence, known as a three-way handshake. The host machine receives a synchronized (SYN) message to begin the “handshake.” The server acknowledges the message by sending an acknowledgement (ACK) flag to the initial host, which then closes the connection. In a SYN flood, however, spoofed messages are sent and the connection doesn’t close, shutting down service.``

#### UDP Flood
``The User Datagram Protocol (UDP) is a sessionless networking protocol. A UDP flood targets random ports on a computer or network with UDP packets. The host checks for the application listening at those ports, but no application is found.``

#### HTTP Flood
``HTTP Flood appears to be legitimate GET or POST requests that are exploited by a hacker. It uses less bandwidth than other types of attacks but it can force the server to use maximum resources.``

#### Ping of Death
`` Ping of Death manipulates IP protocols by sending malicious pings to a system. This was a popular type of DDoS two decades ago, but is less effective today.``

#### Smurf Attack
``A Smurf Attack exploits Internet Protocol (IP) and Internet Control Message Protocol (ICMP) using a malware program called smurf. It spoofs an IP address and using ICMP, it pings IP addresses on a given network.``

#### Fraggle Attack
``A Fraggle Attack uses large amounts of UDP traffic to a router’s broadcast network. It’s similar to a smurf attack, using UDP rather than ICMP.``

#### Slowloris
``Slowloris allows attackers to use minimal resources during an attack and targets on the web server. Once it has connected with its desired target, Slowloris keeps that connection open for as long as possible with HTTP flooding. This type of attack has been used in some high-profile hacktivist DDoSing, including the 2009 Iranian presidential election. DDoS mitigation with this type of attack is very difficult.``

#### Application Level Attacks
``Application Level Attacks exploit vulnerabilities in applications. The goal of this type of attack is not to go after the entire server, but applications with known weaknesses.``

#### NTP Amplification
``NTP Amplification exploits Network Time Protocol (NTP) servers, a long-time network protocol used to synchronize computer clocks, in order to overwhelm UDP traffic. This is an amplified reflection attack. In any reflection attack, there is a response from the server to a spoofed IP address. An amplified version means the response from the server is disproportionate to the original request. Because of the high bandwidth used when DDoSed, this type of attack can be devastating and high volume. ``

#### Advanced Persistent DoS (APDoS)
``Advanced Persistent DoS (APDoS) is an attack type used by hackers who want to cause serious damage. It uses a variety of the styles of attacks mentioned earlier (HTTP flooding, SYN flooding, etc.) and regularly targets multiple attack vectors that send out millions of requests per second. APDoS attacks can last for weeks, largely due to the ability of the hacker to switch tactics at any moment and to create diversions to elude security defenses. ``

#### Zero-day DDoS Attacks
`` Zero-day DDoS attack is the name given to new DDoS attack methods that exploit vulnerabilities that have not yet been patched. ``


### [DDoS HandBook](https://security.radware.com/uploadedFiles/Resources_and_Content/DDoS_Handbook/DDoS_Handbook.pdf)
### [DDos For Dummies](http://crezer.net/Newsletter/archivos/DDoS.pdf)


### Noted by [konova](https://www.facebook.com/kon0va)

### Ref : 
- [Esecurity Planet](https://www.esecurityplanet.com/network-security/types-of-ddos-attacks.html)
