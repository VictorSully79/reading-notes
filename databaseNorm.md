# Database Normalization
Notes taken from: Database Normalization (Explained in Simple English) via essentialsql.com

## What is it?
### Database normalization is a process used to organize a database into tables and columns.
### Databases should be limited in scope in order to reduse the number of duplicated data.

## Three main reasons for Normalization:
- Minimize duplicate data
- Minimize data lost
- Simplify queries

### Three Common forms of normalization:
- 1NF, The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
- 2NF, The table is in first normal form and all the columns depend on the table’s primary key.
3NF,  the table is in second normal form and all of its columns are not transitively dependent on the primary key
