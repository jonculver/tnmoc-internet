# Notes on the birth of the internet

P: 'Where Wizards Stay Up Late' by Katie Hafner & Matthew Lyon

I: The Innovators by Walter Isaacson

P41, I232 - ARPA goal for networking was to save money. Each computer was highly specialized and having every university have one of each was prohibitively expensive. Allowing researchers at one site to use a specific machine located elsewhere. Pizza. Bob Taylor.
 

P59, I240 - Centralized/Decentralized/Distributed. Paul Baran 1960 (BEAR-en). Goal resilience and redundancy to allow military communication to survive nuclear attack. 3-4 redundant links is pretty close to as resilient as full mesh. 

P61 - 'Hot potato routing', routing table at each node with full knowledge of network and path costs. 'adaptive' or 'dynamic' routing - table constantly updated. Not taken forward. 

I240 - Military not interested. AT&T said it wasn't possible and even if it was didn't want to disrupt cosy monopoly. By 1964 published 11 volumes of details entitled 'on distributed communications'. 

P61 - Telephone networks circuit-switched. Once connected circuit remains in use until conversation ends. OK for voice but inefficient for data which is bursty with lots of long pauses. Waste of bandwidth. Packet switching more efficient.

P65 - 1965 Donald Davies coins and proposes packet switching. Motivated by speed and efficiency. Downfall.

P69 - 1965 Tom Marill coins 'protocol' for set of procedures for reliable message passing

P73-75 - Don't want to waste precious cycles on networking + interoperability problems => IMPs. XKCD

P76, I235 - 1967 Larry Roberts presents proposal for ARPA net. Universities didn't want to share (already maxed) or waste cycles dealing with network. Translation problems between OS and language. Taylor and Roberts said they had to or no funding.

P79 - 1968 RFP for ARPA net sent out. 

P103, I252 - Build started in 1969. $1M for 4 IMPs (Modified Honeywell 516). Team led by Frank Heart. P143 - UCLA (Sigma-7), SRI (Stanford) (SDS-940), UC Santa Barbara, University of Utah. Finished in december

I255 - Oct 29 1969 - just after moon landing - UCLA to SRI link activated. L-O-G, bug in autocomplete, crashed
P105 - 0.5s to get from any host to any destination. 100 8K messages per sec broken into 1K packets. 

P109 - 12Kb core memory
P114 - 2 twisted pairs copper
P123 - 32 bit header

P144,I253 - April 1969 - RFC No.1 Host Software. Steve Crocker. described basic handshake between 2 computers (IMP-to-host). Became Network Working Group

P155 - Utah only connected to SRI

P161 - 1970 - 50Kb line from UCLA to Cambridge, Mass. 

P162 - Loopback tests and other CE-like debugging features

P166 - summer 1970. MIT, RAND, System Development Corp, Harvard. MIT to Utah, Camb to RAND. Then Lincoln Laboratory, Stanford, Carnegie-Mellon, Case Western Reserve, Burroughs Corp - Paoli Penn

P171 - 15 IMPs by end 1970 then moved to Honeywell 316. Want to increase host connections from 4 to 63 and allow terminals in place of hosts (TIP)

P174 - 1971 Telnet, FTP July 1972 RFC 354

P175- Autumn 1971 675K packets per day - 2%. Few applications

P178 - August 1972 29 nodes

P191 - 1972 - First email between two computers (Ray Tomlinson), later that year incorporated into FTP as MAIL & MLFL. First use of @ sign 

P187 - September 1973 - temporary satellite link to ARPANET from Brighton, UK

P196 - 1974 nearly 50 IMPs

P212 - 1976 Local area networks with e-mail software was in use in several large corporations

P220 - 1969 Alohanet - 7 stations using radio to send data in Hawaii. SATNET - overtaken by under sea fiber

P222,I258 - 1973 Internetting project to join networks. Vint Cerf & Bob Kahn. Gateway. Looks like a host on both networks, Internet Protocol

P226 - 1974 paper "A protocol for packet network intercommunication". TCP. Assume unreliable network (unlike ARPA). put responsibility on host

P229 - 1975 Arpanet - sales of compute as a service

P236 - 1977 First demonstration of 3 networks communicating. 1978. split IP from TCP

P238 - 1973 Bob Metcalfe adapted Alohanet collision protocol into Ethernet. 

P242- 1979 - Arpanet site $100Kpa to run. Only 15 of 61 at universites. 120 CS departments. => CSNET. 3 tier access model. By 1983 more than 70 sites

P244 - Internet (capital I) around by mid 80s. Routers 
P245- NSFNET backbone

P248 - 1983 - ARPANET transitions from NCP to TCP/IP. 113 nodes but then split into MILNET for military stuff with only 43 remaining in ARPANET. Gateway between them

P250 - 1980 Xerox sell Ethernet as commercial product

P251 - Mid 80s - lots of ethernet LANs with ARPANET in the centre

P252 - 1982 SMTP standardized email, 1983 DNS.

P254 - by late 1980s users could choose NSFNET or ARPANET backbone. 1989 ARPANET turned off