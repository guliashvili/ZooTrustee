Who are we?
We are nerds, learning Rust and how distributed systems work

What's the goal?
1. Create yet another ZooTrustee(ZooKeeper) client in Rust, which should be 100% pluggable with zookeeper 3.5.5 , as the reference zookeeper client C code will be used.
2. Create ZooTrustee(ZooKeeper) server in Rust, which should be able to replace any gracefully shut down ZooKeeper server or join as the new node.

What does success look like?
* We make ourselves comfortable with Rust
* We make ourselves comfortable in understanding how current state of art distributed frameworks work
* We start developing our own non ZooKeeper compatible features
* ZooTrustee proves to be at least 2x faster in all the practical cases
