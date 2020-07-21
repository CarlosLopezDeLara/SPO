---
description: >-
  As explained before, core and relay nodes must run in separate machines. In
  this assignment you will create a second server or Virtual Machine to host
  your core node.
---

# Assignement-2

1. Create a second server on AWS or Virtual Machine in Virtual Box. This one will host core node.
2. Create the directory .local/bin and add it to the PATH 
3. Use `scp` to copy `cardano-node` and `cardano-cli` binaries to this new server. 
4. Alternatively follow  [Installing and running a node ](../getting-started/install-node.md)again to build the node from source in your new server or Virtual Machine. 

{% hint style="info" %}
In any case it is important to make sure that your core and relay nodes run the exact same version of the node. So make sure to update both whenever you have to update to a newer version of the cardano-node. 
{% endhint %}

5. DO NOT START YOUR CORE NODE YET. When you have completed tasks 1-4, continue to [KES-Periods](kes_period.md)


