# Summary

- **Relational DB:** OLTP (Online Transaction Processing), RDS & Aurora(AWS)
- **In mem:** Elasticache. High performance, low latency. Use case -> Take load of DB for read intensive tasks.
- **Key/Val DB:** DynamoDB (serverless), DAX (cache for DynamoDB)
- **Warehouse:** (OLAP: Anyalytics processing) Redshift
- **Hadoop:** EMR (Elastic MapReduce). Creates hadoop cluster to analyze big data. Use Case -> Data processing, ML, Big data
- **Athena:** Query data stored in S3 (serverless and SQL)
- **Quicksight:** Dashboards for data, serverless
- **DocumentDB:** No SQL, AWS proprietary
- **Quantum Ledger DB:** Financial transaction ledger. Immutable, cryptograhically verifiable
- **Managed Blockchain:** Managed hyper ledger fabric & Ethereum Blockchain
- **Glue:** ETL(Extract, Transform, Load) and Data Catalog service.Catalog -> references data used as sources .Serverless
- **DB Migration:** Database migration service