# MongoDB Advance Course — From Basics to Aggregations

This repo contains a full MongoDB course in `.txt` files, focused on hands-on practice using the MongoDB Shell (`mongosh`). It’s designed for developers who prefer reading and experimenting directly in the terminal. Topics range from simple CRUD operations to advanced aggregation pipelines, indexing, schema validation, conditional logic, and database maintenance.

Each file contains real-world examples that can be copy-pasted directly into `mongosh`. Ideal for backend developers and DBAs who want to deepen their MongoDB skills or refresh advanced concepts quickly.

---

## Techniques Demonstrated

This collection emphasizes terminal-first usage of MongoDB with practical, real-world scenarios. Some of the advanced topics and techniques covered:

- [Schema validation using JSON Schema](https://www.mongodb.com/docs/manual/core/schema-validation/)
- [Aggregation pipelines](https://www.mongodb.com/docs/manual/core/aggregation-pipeline/)
- [Advanced query operators](https://www.mongodb.com/docs/manual/reference/operator/query/)
- [Data transformation stages](https://www.mongodb.com/docs/manual/reference/operator/aggregation-project/)
- [Cross-collection joins with `$lookup`](https://www.mongodb.com/docs/manual/reference/operator/aggregation/lookup/)
- [Array operators](https://www.mongodb.com/docs/manual/reference/operator/query-array/) like `$all`, `$elemMatch`, and `$size`
- [Type checking with `$type`](https://www.mongodb.com/docs/manual/reference/operator/query/type/)
- [Capped collections](https://www.mongodb.com/docs/manual/core/capped-collections/)
- [Conditional logic using `$cond`, `$ifNull`](https://www.mongodb.com/docs/manual/reference/operator/aggregation/cond/)
- [Indexing strategies](https://www.mongodb.com/docs/manual/indexes/)
- [Importing JSON with `mongoimport`](https://www.mongodb.com/docs/database-tools/mongoimport/)
- [Backing up and restoring data](https://www.mongodb.com/docs/manual/core/backups/)

---

## Tools and Libraries

- [`mongosh`](https://www.mongodb.com/docs/mongodb-shell/)
- [BSON types](https://www.mongodb.com/docs/manual/reference/bson-types/)
- [JSON Schema](https://json-schema.org/) for validation logic
- [mongoimport](https://www.mongodb.com/docs/database-tools/mongoimport/) for importing data
- MongoDB’s built-in backup and restore tools (`mongodump`, `mongorestore`)

---

## Project Structure

```
/
├── 1_basic.txt
├── 2_insertData.txt
├── 3_datatypes.txt
├── 4_schemaValidation.txt
├── 5_update&Replace.txt
├── 6_deleteDocument.txt
├── 7_findDocuments.txt
├── 8_comparisonOperators.txt
├── 9_logicalOperaters.txt
├── 10_elementOperator.txt
├── 11_EvaluationQueryOpearator.txt
├── 12_findOneUpdate,replace&delete.txt
├── 13_aggregationPipeline.txt
├── 14_aggregationPart2.txt
├── 15_aggregationPart3.txt
├── 16_aggregationPart4.txt
├── 17_aggregationPart5.txt
├── 18_aggregationPart6.txt
├── 19_aggregationPart7.txt
├── 20_arithmaticOperaotr.txt
├── 21_stringOperators.txt
├── 22_dateOperators.txt
├── 23_arrayOperators.txt
├── 24_typeOperators.txt
├── 25_cappedCollection.txt
├── 26_conditional.txt
├── 27_indexes.txt
├── 28_importJSON.txt
├── 29_backup.txt
├── 30_authentication&UserManagment.txt

```

Each file is a standalone guide with practice-ready shell code and inline explanations. No directories or nested folder structures are used.
