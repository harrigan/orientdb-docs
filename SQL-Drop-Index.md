# SQL - `DROP INDEX`

Removes an index from a property defined in the schema.

**Syntax**

```sql
DROP INDEX <index>|<class>.<property>
```

- **`<index>`** Defines the name of the index.
- **`<class>`** Defines the class the index uses.
- **`<property>`** Defines the property the index uses.

**Examples**

- Remove the index on the `Id` property of the `Users` class:

  <pre>
  orientdb> <code class="lang-sql userinput">DROP INDEX Users.Id</code>
  </pre>


>For more information, see
>- [`CREATE INDEX`](SQL-Create-Index.md)
>- [Indexes](Indexes.md)
>- [SQL Commands](SQL.md)