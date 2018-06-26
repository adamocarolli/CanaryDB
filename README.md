# CanaryDB

CanaryDB aims to be a simple, fast key-value (KV) storage library. 

## Why implement a key-value store

There are a batch of fantastic open-source key-value stores available such as Google's [LevelDB](https://github.com/google/leveldb), Facebook's [RocksDB](https://github.com/facebook/rocksdb) and DGraph's [BadgerDB](https://github.com/dgraph-io/badger). So why bother building another key-value store? 

The short of it is that I don't know how these systems work, but I'd like to! A longer answer takes from Emmanuel Goossaert's [article](http://codecapsule.com/2012/11/07/implementing-a-key-value-store-part-1-what-are-key-value-stores-and-why-implement-one/), I was looking for a project that would allow me to review:

* The C++ programming language
* Object-oriented design
* Algorithmics and data structures
* Memory management
* Concurrency control with multi-processors or multi-threading
* Networking with a server/client model
* I/O problems with disk access and use of the file system
* Distributed systems

The moonshot answer is, although CanaryDB is starting out as a learning project, I am hopeful that throughout the course of its development we will find and focus on a niche left unfulfilled by the other projects out there that'd provide positive impact.
