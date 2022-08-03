FurDB is a Relational Database Management System that allows you to allot the size of the value in bits, significantly reducing the space occupied by the data. Conversion between the data and the bits stored in the database is done by an external service.

To get started, you can add [FurDB](https://github.com/furdb/furdb) as a dependency in a Rust project, or you can use its Actix-powered [REST API implementation](https://github.com/furdb/furdb-server) for any Rust or non-Rust project and follow their respective documentations. You would also need a server to handle data conversions such as [Fur Converter](https://github.com/furdb/fur-converter).

There is a sample [Dictionary Demo](https://github.com/furdb/fur-dictionary) application powered by FurDB that you can play around with!
