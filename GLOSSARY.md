# 📖 Glossary

Short definitions of terms from my notes, in alphabetical order. Each links to the note where it comes up.

| Term | Meaning | Note |
|---|---|---|
| ACID | Atomicity, Consistency, Isolation, Durability: guarantees that a database transaction either fully happens or doesn't happen at all, and stays correct | [01](notes/01-database.md) |
| Blob | Binary Large Object: a big file like an image, video or backup, usually kept in storage like S3 | [01](notes/01-database.md) |
| Eventual consistency | Copies of data may differ for a short time, but they all catch up to the same value | [01](notes/01-database.md) |
| Horizontal scaling (scale out) | Adding more machines and spreading the work across them | [02](notes/02-horizontal-vs-vertical-scaling.md) |
| Load balancer | A component that sends each incoming request to one of several servers | [02](notes/02-horizontal-vs-vertical-scaling.md) |
| NoSQL | A family of non-relational databases (key-value, document, wide-column, graph) built for scale or flexibility | [01](notes/01-database.md) |
| Polyglot persistence | Using several types of databases in one system, each for the job it's best at | [01](notes/01-database.md) |
| Single point of failure | One part that, if it breaks, takes the whole system down | [02](notes/02-horizontal-vs-vertical-scaling.md) |
| Stateless | A server that doesn't keep user data between requests, so any server can handle any request | [02](notes/02-horizontal-vs-vertical-scaling.md) |
| Vertical scaling (scale up) | Making one machine bigger: more CPU, RAM or storage | [02](notes/02-horizontal-vs-vertical-scaling.md) |
