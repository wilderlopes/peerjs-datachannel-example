# Simple message exchange between two peers using RTCDataChannel and peerJS

1. Open the receiver.html first and then open the browser console
2. Open the sender.html and the browser console

There are two receiver peers: one local (same tab as the sender), defined right after the sender peer 
on the sender.html file; one remote, defined in the receiver.html file.

You can choose the destination peer (local or remote) by setting the destinationPeerID variable
defined inside the script session of sender.html. By default, it is set to be the remote peer.

Check the messages in the browser console of each tab (sender.html and receiver.html) 
to see the sequence of events in the message exchange.
