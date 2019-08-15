# India_Annual_Health_Survey_DataAnalysis_using_Hive

Ingest the India Annual Health Survey (AHS) 2012-13 data hosted on Amazon RDS into Hadoop correctly and process it to generate the following analyses:


1. The child mortality rate in Uttar Pradesh
2. The fertility rate in Bihar
3. State-wise child mortality rate and state-wise fertility rate and does high fertility correlate with high child mortality?
4. Find top 2 districts per state with the highest population per household
5. Find top 2 districts per state with the lowest sex ratios

Such analyses would help in vivid understanding and timely monitoring of different determinants on well-being and health of population particularly Child and Reproductive Health. Based on the analyses, one can also compare India’s position in Global HDI and can suggest ways that can improve it.

### Guidelines
1. Ingest data from Amazon RDS to HDFS using Sqoop.

2. Create an external table in Hive for the ingested data containing all the columns as given in this document. Ingest the data from HDFS to the Hive table. Verify that the ingestion is successfully accomplished.

3. Create a subset schema in Hive to store the data for the analyses to be done. The schema should be optimized to support ONLY the analyses to be done. You will be graded on your choice of the chosen columns, storage format (Parquet, RC, ORC, CSV), etc. Benchmark the performance of the storage formats before finalizing the one to be used.

4. Write queries against each category of analyses. You will be graded on the relevance of your query to the analytical use case and the optimizations used. Generate the corresponding analyses’ charts on Hue.
