# MongoDB Advance 🍃

> A complete MongoDB course in 30 hands-on `.txt` files — from basic CRUD to advanced aggregation pipelines, indexing, schema validation, and database maintenance. Run everything directly in `mongosh`.

No videos, no slides. Just real shell commands with inline explanations, copy-pasteable into your terminal. Each file is a self-contained lesson you can work through at your own pace.

---

## Table of Contents

- [Who This Is For](#who-this-is-for)
- [How to Use](#how-to-use)
- [Course Outline](#course-outline)
- [Prerequisites](#prerequisites)
- [Tools Used](#tools-used)
- [About](#about)

---

## Who This Is For

- Backend developers who want to go beyond basic `find()` and `insert()`
- Developers using MongoDB in production who want to understand aggregations deeply
- Anyone who learns better by running commands than watching lectures
- DBAs or engineers who need a quick reference for advanced MongoDB operations

---

## How to Use

1. Clone the repo:

```bash
git clone https://github.com/Wcoder547/Mongdb_advance.git
cd Mongdb_advance
```

2. Open any `.txt` file — each one is a standalone lesson with commands and explanations.
3. Open your terminal and start `mongosh`:

```bash
mongosh
```

4. Copy the commands from the file and run them directly in the shell.

No installation beyond MongoDB itself. No dependencies. No setup.

---

## Course Outline

The files are numbered in learning order — start at `1_basic.txt` and work forward, or jump to any topic you need.

### Foundations

| File | Topic |
|---|---|
| `1_basic.txt` | Database creation, collections, basic shell usage |
| `2_insertData.txt` | `insertOne`, `insertMany`, bulk inserts |
| `3_datatypes.txt` | BSON types — strings, numbers, dates, ObjectId, arrays, embedded docs |
| `4_schemaValidation.txt` | JSON Schema validation on collections |
| `5_update&Replace.txt` | `updateOne`, `updateMany`, `replaceOne` |
| `6_deleteDocument.txt` | `deleteOne`, `deleteMany` |
| `7_findDocuments.txt` | `find`, `count`, `sort`, `limit`, projection |

### Query Operators

| File | Topic |
|---|---|
| `8_comparisonOperators.txt` | `$eq`, `$ne`, `$gt`, `$gte`, `$lt`, `$lte`, `$in`, `$nin` |
| `9_logicalOperaters.txt` | `$and`, `$or`, `$not`, `$nor` |
| `10_elementOperator.txt` | `$exists`, `$type` |
| `11_EvaluationQueryOpearator.txt` | `$regex`, `$mod`, `$expr`, `$where` |
| `12_findOneUpdate,replace&delete.txt` | `findOneAndUpdate`, `findOneAndReplace`, `findOneAndDelete` |

### Aggregation Pipelines

| File | Topic |
|---|---|
| `13_aggregationPipeline.txt` | Pipeline basics — `$match`, `$group`, `$project`, `$sort` |
| `14_aggregationPart2.txt` | `$push`, `$addToSet`, accumulators |
| `15_aggregationPart3.txt` | `$lookup` (joins), `$replaceRoot` |
| `16_aggregationPart4.txt` | `$bucket`, `$bucketAuto` |
| `17_aggregationPart5.txt` | `$addFields`, `$unwind` |
| `18_aggregationPart6.txt` | `$out`, `$merge`, `$unionWith` |
| `19_aggregationPart7.txt` | `$facet`, `$fill` |

### Operators Inside Aggregations

| File | Topic |
|---|---|
| `20_arithmaticOperaotr.txt` | `$add`, `$subtract`, `$multiply`, `$divide`, `$mod` |
| `21-stringOperators.txt` | `$concat`, `$toLower`, `$toUpper`, `$dateToString`, `$indexOfBytes` |
| `22_dateOperators.txt` | `$year`, `$month`, `$dayOfWeek`, `$dateSubtract`, etc. |
| `23_arrayOperators.txt` | `$size`, `$arrayElemAt`, `$filter`, `$map`, `$reduce` |
| `24_typeOperators.txt` | `$toInt`, `$toString`, `$toDate`, `$convert` |
| `26_conditional.txt` | `$cond`, `$ifNull`, `$switch` |

### Database Administration

| File | Topic |
|---|---|
| `25_cappedCollection.txt` | Capped collections — fixed-size, auto-expiry |
| `27_indexes.txt` | Single, compound, text, and geospatial indexes; `explain()` |
| `28_importJSON.txt` | `mongoimport` — importing JSON datasets |
| `29_backup.txt` | `mongodump` and `mongorestore` for backups |
| `30_authentication&UserManagment.txt` | Creating users, roles, enabling auth in `mongod` |

---

## Prerequisites

- MongoDB installed locally ([install guide](https://www.mongodb.com/docs/manual/installation/))
- `mongosh` shell available in your terminal
- Basic understanding of what a database and collection are — everything else is taught from file 1

---

## Tools Used

- **mongosh** — MongoDB's official interactive shell
- **BSON types** — MongoDB's binary data format
- **JSON Schema** — for collection-level schema validation
- **mongoimport** — for importing JSON/CSV datasets
- **mongodump / mongorestore** — for backup and restore operations

---

## About

This repo came out of going through MongoDB seriously — not just enough to hook it up to an Express app, but understanding how the query engine works, how aggregation pipelines transform data, how indexes affect performance, and how to manage a database in production.

The `.txt` format was a deliberate choice: no framework, no tooling, just you and the shell. Every command in here has been run and verified. It's the reference I wished existed when I was learning.

**Built by [Waseem Akram](https://www.linkedin.com/in/wasim-akram-dev/)** — Full-Stack Developer and DevOps Engineer based in Pakistan, working across the MERN stack, Generative AI integrations, and cloud automation.

---

*If this helped you, consider giving it a ⭐ — it helps others find it.*
