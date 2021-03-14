# Notes on 'Where Wizards Stay Up Late' by Katie Hafner & Matthew Lyon

P41 - ARPA goal for networking was to save money. Each computer was highly specialized and having every university have one of each was prohibitively expensive. Allowing researchers at one site to use a specific machine located elsewhere. Pizza. Bob Taylor.

P59 - Centralized/Decentralized/Distributed. Paul Baran 1960. Goal resilience and redundancy to allow military communication to survive nuclear attack. 3-4 redundant links is pretty close to as resilient as full mesh. 

P61 - 'Hot potato routing', routing table at each node with full knowledge of network and path costs. 'adaptive' or 'dynamic' routing - table constantly updated. Not taken forward.

P61 - Telephone networks circuit-switched. Once connected circuit remains in use until conversation ends. OK for voice but inefficient for data which is bursty with lots of long pauses. Waste of bandwidth. Packet switching more efficient.

P65 - 1965 Donald Davies coins and proposes packet switching. Motivated by speed and efficiency. Downfall.

P69 - 1965 Tom Marill coins 'protocol' for set of procedures for reliable message passing

P73-75 - Don't want to waste precious cycles on networking + interoperability problems => IMPs. XKCD

P76 - 1967 Larry Roberts presents proposal for ARPA net. UCLA

P79 - 1968 RFP for ARPA net sent out. 

P103 - Build started in 1969. $1M for 4 IMPs (Modified Honeywell 516). Team led by Frank Heart. P143 - UCLA (Sigma-7), SRI (SDS-940), UC Santa Barbara, University of Utah. Finished in december

P105 - 0.5s to get from any host to any destination. 100 8K messages per sec broken into 1K packets. 

P109 - 12Kb core memory
P114 - 2 twisted pairs copper
P123 - 32 bit header

P144 - April 1969 - RFC No.1 Host Software. Steve Crocker. described basic handshake between 2 computers. Became Network Working Group

P155 - Utah only connected to SRI

P161 - 1970 - 50Kb line from UCLA to Cambridge, Mass. 

P162 - Loopback tests and other CE-like debugging features

P166 - summer 1970. MIT, RAND, System Development Corp, Harvard. MIT to Utah, Camb to RAND. Then Lincoln Laboratory, Stanford, Carnegie-Mellon, Case Western Reserve, Burroughs Corp - Paoli Penn

P171 - 15 IMPs by end 1970 then moved to Honeywell 316. Want to increase host connections from 4 and allow terminals in place of hosts