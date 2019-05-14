# DeSign 

DeSign is an optimized BitTorrent’s P2P data exchange and storage protocol. It obtains data blocks from other files and computes the hash values. As long as the hash values of the data blocks are matching, the data contents of those blocks will be the same.

The DeSign is far more efficient than BitTorrent since it has a complete incentive mechanism to encourage data sharing. The credit value of a node will drop if it only does data receiving and not sending. Once the node's credit value goes down to a certain point, the node will be ignored by others and kicked out in the end.

