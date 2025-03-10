[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/SQL-statement-syntax/refresh-materialized-view.md)

# Refresh Materialized View

The `Refresh Materialized View` section of the app technical guide covers the process of initially populating or refreshing the data stored in a materialized view. The materialized view must be defined with `create-materialized-view`. The data is retrieved from the underlying tables accessed by the defined query.

The initial population of the materialized view can be processing intensive since it reads the data from the source tables and performs physical write operations. The refresh operation can be less intensive if the underlying data has not changed and the connector has implemented a mechanism to be aware of that. The specific implementation and performance varies by connector used to create the materialized view.

The `Synopsis` section provides a code snippet that shows the syntax for refreshing a materialized view. The `Description` section provides a detailed explanation of the process of refreshing a materialized view, including the fact that the materialized view must be defined with `create-materialized-view`. The section also explains that the initial population of the materialized view can be processing intensive, and that the refresh operation can be less intensive if the underlying data has not changed.

The `See also` section provides links to related sections of the app technical guide, including `create-materialized-view`, `drop-materialized-view`, and `show-create-materialized-view`.

Example:

To refresh a materialized view named `sales_data`, the following code can be used:

``` text
REFRESH MATERIALIZED VIEW sales_data
```
## Questions: 
 1. What is the purpose of the `REFRESH MATERIALIZED VIEW` command in the context of a blockchain SQL database?
- Answer: A blockchain SQL analyst might want to know how this command can be used to update or retrieve data from materialized views in the blockchain database.

2. How does the performance of the `REFRESH MATERIALIZED VIEW` command vary depending on the connector used to create the materialized view?
- Answer: A blockchain SQL analyst might want to understand how different connectors can affect the performance of this command when working with materialized views in the blockchain database.

3. Are there any security considerations or limitations when using the `REFRESH MATERIALIZED VIEW` command in the context of a blockchain SQL database?
- Answer: A blockchain SQL analyst might want to know if there are any security risks or limitations associated with using this command to update or retrieve data from materialized views in the blockchain database.