# Structured Query Language Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

Please _read_ the following from the [PostgreSQL
Documentation](http://www.postgresql.org/docs/9.5/static/index.html):

-   The [Preface](http://www.postgresql.org/docs/9.5/static/preface.html)
excluding [Bug Reporting
Guidelines](http://www.postgresql.org/docs/9.5/static/bug-reporting.html).
-   In Part I. [Tutorial](http://www.postgresql.org/docs/9.5/static/tutorial.html)

    -   Chapter 1. [Getting Started](http://www.postgresql.org/docs/9.5/static/tutorial-start.html)
    -   Chapter 2. [The SQL Language](http://www.postgresql.org/docs/9.5/static/tutorial-sql.html).

You are not expected to create tutorial files as described in [2.1.
Introduction](http://www.postgresql.org/docs/9.5/static/tutorial-sql-intro.html).

## Notation conventions

What characters denote optional parts of a command?
Show the characters and give their name.

```md

"[]" square brackets are not typed and indicate that whatever is enclosed is optional syntax

<!-- used:
https://docs.oracle.com/cd/B14156_01/doc/B13812/html/sqcmd.htm -->
```

What characters indicate a possible repeating element in a command?
Show the characters and give their name.

```md

if ellipsis points follow after a second appearance of a bracketed term, it indicates loops or repetitions.
The bracketed part indicates that the repetition is optional.

<!-- used:
https://docs.oracle.com/cd/B14156_01/doc/B13812/html/sqcmd.htm -->
```

## Creating or removing a database

What shell command would you execute to create a database named `mydb`?

```sh

$ createdb mydb

# used:
# documentation
```

What shell command would you execute to remove a database named `mydb`?

```sh

$ dropdb mydb

# used:
# documentation
```

## Creating or removing a table

What two SQL keywords precede the table name when creating a database table?

```sql
CREATE TABLE <name>;
```

What is the SQL command to remove a database table named `mytable`?

```sql
DROP TABLE mytable;
```

## Table row CRUD

What two SQL keywords precede the table name when populating
a database table with rows?

```sql
INSERT INTO <table_name>;
```

What SQL keyword starts the command to retrieve data from a database table?

```sql
SELECT * FROM
```

What SQL command is used to update existing rows in a database table?

```sql
UPDATE <table_name>
SET <column_name>
WHERE <condition>
```

What SQL command is used to remove rows from a database table?

```sql
DELETE FROM <table_name>
WHERE <condition>
```
