# Indexing
Currently the plan for indexing is using the node to request all block and transaction data one by one and put it into a database. This is very time consuming so should be done early in development. This syncer will run parallel to the backend but wont communicate directly with the backend but only through the database.
- Database: PostegreSQL
- Sync: Python/Java/Node (Don't know yet)

# Web
For web / backend react next.js will most probaply be used. This is not 100% sure yet but server side rendering would be nice to prevent a free public API for everyone to use.

- Web: React / Next.js
- ORM: Prisma
