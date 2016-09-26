# 1.0.0

* Removed farmhash and msgpack (default build issues)

# 1.0.1

* Merged upstream join-sync includes faulty-list 

# 1.0.2 25-09-2016

* Used join-sync's faulty-list to repopulate member's faulty-list thus preserving it indefinitely through the cluster.

# 1.0.3 26-09-2016

* Made each member the sole authority on it's metadata. 