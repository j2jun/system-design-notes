# 📘 System Design Notes

My notes from learning system design, one topic at a time. Each note is short and simple: what it is, examples, when to use it, and the trade-offs.

**How I use this repo:** read a topic, copy [the note template](TEMPLATE.md) into the `notes` folder, fill it in, then tick the box below.

## 📊 Tracker

**Progress: 1 of 12 fundamentals done**

### 🧱 Fundamentals

- [ ] 01 · Database · [Database article](https://lnkd.in/gti8gjpz)
- [x] 02 · [Horizontal vs Vertical Scaling](notes/02-horizontal-vs-vertical-scaling.md) · done 2026-11-06
- [ ] 03 · Caching · [Caching article](https://lnkd.in/gC9piQbJ)
- [ ] 04 · Distributed Caching · [Distributed caching article](https://lnkd.in/g7WKydNg)
- [ ] 05 · Load Balancing · [Load balancing article](https://lnkd.in/gQaa8sXK)
- [ ] 06 · SQL vs NoSQL · [SQL vs NoSQL article](https://lnkd.in/g3WC_yxn)
- [ ] 07 · Database Scaling · [Database scaling article](https://lnkd.in/gAXpSyWQ)
- [ ] 08 · Data Replication · [Data replication article](https://lnkd.in/gVAJxTpS)
- [ ] 09 · Data Redundancy · [Data redundancy article](https://lnkd.in/gNN7TF7n)
- [ ] 10 · Database Sharding · [Database sharding article](https://lnkd.in/gMqqc6x9)
- [ ] 11 · Database Indexes · [Database indexes article](https://lnkd.in/gCeshYVt)
- [ ] 12 · Proxy Server · [Proxy server article](https://lnkd.in/gi8KnKS6)

### 🏗️ Design problems (later)

- [ ] Design Ticketmaster
- [ ] Design Tinder

## ✍️ Adding a topic

1. Copy `TEMPLATE.md` to `notes/NN-topic-name.md` (for example, `notes/03-caching.md`).
2. Fill in the sections with short bullets. Add a diagram or table when it makes the idea clearer.
3. In the tracker: change `[ ]` to `[x]`, link the topic name to the note, add "done" and the date, and update the progress count.
4. Commit with a message like `Add 03 caching notes`.

## ♿ Note style (keep every note consistent)

**Emoji:** one emoji at the start of each section heading, always the same set:

| Emoji | Section |
|---|---|
| 📅 | Date |
| 📚 | Resources |
| 💡 | In one sentence |
| 🗺️ | Diagram |
| 🔑 | Key ideas |
| 🧪 | Examples |
| 🎯 | When to use it |
| ⚖️ | Trade-offs |
| ☁️ | On AWS |
| 🎤 | Interview one-liner |
| ❓ | Questions I still have |

**Accessibility:**

- **Emoji are decoration only.** They never replace words, and there's only one per heading so screen readers don't read a long string of emoji names.
- **Every diagram has `accTitle` and `accDescr`** inside the Mermaid code (screen readers read these), plus a short **text version** under the diagram.
- **Link text says where it goes**, like "Caching article", never "click here" or "link".
- **Every table has a header row**, and no header cell is left blank.
- **Meaning never depends on color or emoji alone.** Status is a checkbox plus words.
- **Plain language:** short sentences, and acronyms are spelled out the first time they appear.
