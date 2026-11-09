# 📖 Glossary

Short definitions of terms from my notes, in alphabetical order. Each links to the note where it comes up.

| Term | Meaning | Note |
|---|---|---|
| ACID | Atomicity, Consistency, Isolation, Durability: guarantees that a database transaction either fully happens or doesn't happen at all, and stays correct | [Database Types](notes/database-types.md) |
| Blob | Binary Large Object: a big file like an image, video or backup, usually kept in storage like S3 | [Database Types](notes/database-types.md) |
| Cache | A small, fast store that keeps copies of frequently used data so requests don't have to reach the slower original source | [Caching](notes/caching.md) |
| Cache hit / cache miss | A hit is when the requested data is found in the cache; a miss is when it isn't and must be read from the original source | [Caching](notes/caching.md) |
| Cache invalidation | Updating or removing a cached copy when the original data changes, so users don't see stale data | [Caching](notes/caching.md) |
| CDN | Content Delivery Network: servers around the world that keep copies of static files close to users | [Caching](notes/caching.md) |
| Consistent hashing | A way to split keys across cache or database nodes so that adding or removing a node moves only a few keys | [Caching](notes/caching.md) |
| Eventual consistency | Copies of data may differ for a short time, but they all catch up to the same value | [Database Types](notes/database-types.md) |
| Eviction policy | The rule a full cache uses to choose what to remove, such as LRU (Least Recently Used) or LFU (Least Frequently Used) | [Caching](notes/caching.md) |
| Horizontal scaling (scale out) | Adding more machines and spreading the work across them | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) |
| Load balancer | A component that sends each incoming request to one of several servers | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) |
| Locality of reference | Data that was used recently, or data near it, is likely to be used again soon | [Caching](notes/caching.md) |
| LRU | Least Recently Used: an eviction policy that removes the item that hasn't been used for the longest time | [Caching](notes/caching.md) |
| NoSQL | A family of non-relational databases (key-value, document, wide-column, graph) built for scale or flexibility | [Database Types](notes/database-types.md) |
| Polyglot persistence | Using several types of databases in one system, each for the job it's best at | [Database Types](notes/database-types.md) |
| Single point of failure | One part that, if it breaks, takes the whole system down | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) |
| Stateless | A server that doesn't keep user data between requests, so any server can handle any request | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) |
| Vertical scaling (scale up) | Making one machine bigger: more CPU, RAM or storage | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) |
| Write-around cache | Writes go straight to the database and skip the cache; reading just-written data is a cache miss | [Caching](notes/caching.md) |
| Write-back cache | Writes go only to the cache and are copied to the database later; fastest writes but risks data loss | [Caching](notes/caching.md) |
| Write-through cache | Writes go to the cache and the database, and succeed only when both do; always consistent but slower writes | [Caching](notes/caching.md) |
