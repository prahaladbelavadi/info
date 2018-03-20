---

Hacking a Blockchain
This article talks about how a Nation state actors would attempt to hack or gain control of a bitcoin or an ethereum blockchain.


---

Among the many already well known attacks there exist in the security field, below listed are attacks that are most probable to be undertaken by someone with large resources of a nation state actor.
Breaking employed Cryptography using Quantum Computers
SHA256 is a one way hash function employed in most blockchains. The chain of blocks containing transactions are said to be immutable for the hashes of each block is linked to its previous block and it to the one before it and so forth. 
Any change in a block would result in a different hash than the one that already exists implying that the changes to the blockchain are permanent.
The chance of a collision existing is miniscule and to find out, there is a 1 in over 115 quattuorvigintillion (that’s a 78 digit number) chance of finding a collision within SHA256.
This number is exponentially bigger than the number of atoms in the perceivable universe. The fastest Quantum computer that exists today is IBM’s 50 Qubit computer that lasts in a quantum state for 90 Microseconds.
It has been estimated that SHA-256 needs roughly around 2166 “logical qubit cycles” to crack.
If the quantum correction is handled by ASICs running at a few million hashes per second, Grover’s algorithm would need about 10^32 years to crack SHA-256 or SHA3–256.
That’s considerably longer than the mere 14 billion years the universe has existed, although less than the estimated 10^100 years until the heat death of the universe. Even if you didn’t care about the circuit footprint and used a billion-hash-per-second Bitcoin-mining ASIC, the calculation still seems to be in the order of 10^29 years.
Brute forcing a hash function is exhaustive and expensive, even with quantum computer.
51% attack
Also termed Majority attack, 51% attack are an attack on the network with an intent to fork/remove an already existing transaction on the blockchain.
Each node upholds the network by keeping a copy of it.
Miners append transaction filled blocks to existing blockchains, in this case the bitcoin or ethereum blockchain. Any person that controls greater than 50% of the total ability to hash or otherwise called hashpower can be expected to conduct a 51% majority attack in their own best interests.
A majority attack can result in a successful double spend within a given time frame.
Here’s the current mining power distribution.
Given that a majority 51% attack requires that a single entity must control 51% of the hashrate, every additional person running a node decreases the chance of a single entity achieving this kind of power easily. 
It is encouraged for everyone to run their own node. This makes it significantly harder for an attacker to break the system.


A nation state entity can expend resources to gain massive hash power in an attempt to double spend or even shake the trust within the system, however if every person were to run their own nodes and mined accordingly, it is highly unlikely that any nation state entity independently can amass that amount of hashpower to skew this model. 
Not only is it highly unlikely, it would need to be repeated over several cycles and since proof of work is dependent on finding the nonce, there is a luck involved. To conduct a 51% attack, apart from exorbitantly expensive resources, repeated occurence of luck is required which isn’t constant.
Hence, this method is infeasible.
Eclipse attacks:
This attack involves surrounding an individual node’s incoming and outgoing connections with rogue nodes.
Agenda being such that if we can connect our rogue nodes to a possibly unsuspecting node’s ports such that they are surrounded with our attacker nodes. Once we manage to surround the unsuspecting node completely, we can manipulate the ledger according to our will.
 If a nation state actor were to implement this, they’d need enough nodes to surround not just one unsuspecting node but rather greater 50% of the nodes on the network. 
To isolate each node on the bitcoin network, a cumulative of 135 connections are required. The numbers on ethereum differ a little, but are very similar.
This is highly improbable for the fact that if an entity needed to establish 135 nodes to disparage a single node, they are better of conducting a 51% Majority attack instead.
Flooding the mempool with dust transactions:
This isn’t much of a risk as much as it does slow down transactions being added to the blockchain but it clogs the network resulting in significantly longer confirmation time. 
Flooding the mempool involves making tons of low value transactions.
