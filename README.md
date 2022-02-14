# PostgreSQL

## Database Design Process

1. What kind of thing are we storing?
2. What properties does this thing have?
3. What *type* of data does each of those properties contain?

## Lingo

- Keywords: Tell the database that we want to do something. Always writtin in all uppercase.
- Identifiers: Tell the database what thing we want to act on. Always writtin in all lowercase.

## Approaching Database Design

1. Common features are frequently built with conventional table names and columns.
2. What type of resources exist in the application? Create a separate table for each of these features.
3. Features that indicate a relationship or ownership between two types of resources need to be reflected in our table design.