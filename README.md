# 📘 System Design Notes

My notes from learning system design, one topic at a time. Each note is short and simple: what it is, examples, when to use it, and the trade-offs.

**How I use this repo:** read a topic, copy [the note template](TEMPLATE.md) into the `notes` folder, fill it in, then add it to the learning log below. Terms are collected in the [glossary](GLOSSARY.md).

> [!NOTE]
> **How these notes are made:** I write the "In my own words" sections, key takeaways and "Try it" results myself. AI helps me organize, format and draw diagrams.

## 📅 Learning log

What I learned and when, newest first. **Still to finish** lists the parts of a note I haven't done yet; it's empty once the note is complete.

| Date | Topic | Still to finish |
|---|---|---|
| 2026-11-09 | [Caching](notes/caching.md) | 🛠️ Try it |
| 2026-11-06 | [Horizontal vs Vertical Scaling](notes/horizontal-vs-vertical-scaling.md) | ✍️ In my own words · 🧪 Example from my work · 🛠️ Try it |
| 2026-11-06 | [Database Types](notes/database-types.md) | ✍️ In my own words · 🛠️ Try it |

## 📚 Reading list

Topics and resources I want to read next. When I read one, I move it to the learning log.

<details>
<summary><b>Show reading list (11)</b></summary>

| Topic | Resource |
|---|---|
| Distributed Caching | [Distributed caching article](https://lnkd.in/g7WKydNg) |
| Load Balancing | [Load balancing article](https://lnkd.in/gQaa8sXK) |
| SQL vs NoSQL | [SQL vs NoSQL article](https://lnkd.in/g3WC_yxn) |
| Database Scaling | [Database scaling article](https://lnkd.in/gAXpSyWQ) |
| Data Replication | [Data replication article](https://lnkd.in/gVAJxTpS) |
| Data Redundancy | [Data redundancy article](https://lnkd.in/gNN7TF7n) |
| Database Sharding | [Database sharding article](https://lnkd.in/gMqqc6x9) |
| Database Indexes | [Database indexes article](https://lnkd.in/gCeshYVt) |
| Proxy Server | [Proxy server article](https://lnkd.in/gi8KnKS6) |
| Design Ticketmaster | Resource to be added |
| Design Tinder | Resource to be added |

</details>

**To add something:** add a row with the topic and a descriptive link, and update the count in "Show reading list (N)".

## ✍️ Adding a topic

1. Copy `TEMPLATE.md` to `notes/topic-name.md` (lowercase, words joined with dashes, for example `notes/caching.md`).
2. Fill in the sections with short bullets. Add a diagram or table when it makes the idea clearer.
3. Remove it from the reading list (if it was there) and add a row to the **top** of the learning log:

   ```markdown
   | 2026-11-08 | [Caching](notes/caching.md) | ✍️ In my own words · 🛠️ Try it |
   ```

4. When you finish a section later, remove it from **Still to finish**. When nothing is left, write `—`.
5. Add any new terms to the [glossary](GLOSSARY.md).
6. Commit with a message like `Add caching notes`.

**Hidden prompts:** the template has reminders in `<!-- comments -->`. You see them while editing, but they don't show on the page.

**When I review a note later:** add a row to its 🔁 Review log, answer a ❓ question, or finish its 🛠️ Try it.

## 🎨 Note style (keep every note consistent)

**Emoji:** one emoji at the start of each section heading, always the same set:

| Emoji | Section |
|---|---|
| 📌 | Key takeaway (the "Important" box at the top) |
| 📅 | Date |
| 📚 | Resources |
| ✍️ | In my own words |
| 🗺️ | Diagram |
| 🔑 | Key ideas |
| 🧪 | Examples |
| 🎯 | When to use it |
| ⚖️ | Trade-offs |
| ☁️ | On AWS |
| 🛠️ | Try it |
| 🎤 | Interview one-liner |
| 🧠 | Self-check |
| 🔗 | Related topics |
| ❓ | Questions I still have |
| 🔁 | Review log |

**Accessibility:**

- **Emoji are decoration only.** They never replace words, and there's only one per heading so screen readers don't read a long string of emoji names.
- **The key takeaway uses GitHub's `[!IMPORTANT]` box**, which shows the word "Important" as a label, so its meaning doesn't depend on color. Keep it to one sentence and at most 3 bullets.
- **Every diagram has `accTitle` and `accDescr`** inside the Mermaid code (screen readers read these), plus a short **text version** under the diagram.
- **Link text says where it goes**, like "Caching article", never "click here" or "link".
- **Every table has a header row**, and no header cell is left blank.
- **Meaning never depends on color or emoji alone.** Every emoji in the learning log sits next to words.
- **Plain language:** short sentences, and acronyms are spelled out the first time they appear.
