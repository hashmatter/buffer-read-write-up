# buffer-read-write-up

`buffer-read-write-up` is a sporadic newsletter filled with great content on
decentralization and metadata resistant systems. Got an idea or suggestion? 
[Open an issue!](https://github.com/gpestana/notes/issues)

## Batch 18-01

### papers

- [x] [Crawling the DHT for fun and profit](https://www.usenix.org/event/woot10/tech/full_papers/Wolchok.pdf)

Ever wondered who's downloading what in BitTorrent? Scott Wolchok and J. 
Alex Halderman, the authors of "Crawling the DHT for fun and profit" show how
easy and cheap it is to crawl the BitTorrent Vuze DHT to get insights of which 
IP:port pairs are storing and requesting files in the network. They show how
the crawler they built can a new trackers index with millions of entries in a 
question of hours and how it can track more than 8M ips downloading over 1.5M 
files in 16 days.

For more info, check the [original paper](https://dl.acm.org/citation.cfm?id=1773921) or the [short summary](https://github.com/gpestana/notes/blob/master/research/metadata_resistant_dht/deep_imgint/README.md).


- [x] [Consistency without concurrency control in large, dynamic systems](https://dl.acm.org/citation.cfm?id=1773921)

The authors propose a two-tier architecture for performing safe garbage collection in
CRDTs and a migration protocol for upgrading replicas to the highest, updated  tier. The
replicas which are part of the tier-1 (core) maintain and perform operations on
the state which has been through the latest garbage collection in the network.
The second tier of replicas hasn't performed one or more garbage collection
operations. Thus, tier-2 replicas can only perform // TODO: finish! 

### articles

- [The future-proof cryptographic hashes](https://pascalprecht.github.io/posts/future-proofed-hashes-with-multihash/)

// TODO: description

### others

- [Textile Build - Free online workshop about the decentralized
  web](https://medium.com/textileio/announcing-textile-build-a-free-online-workshop-27472fd5d913)

// TODO: description

- [Awesome IPFS](https://awesome.ipfs.io/) just got even more awesome

// TODO: description

---

## Batch X
### papers
- [x] [paper_01](https://paper01.com)
### articles
- [ ] [article_01](https://article01.com)
### others
- [other_01](https://other01.com)

