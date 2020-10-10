# Used_case
User case: NSE India,

domain: Stock Market

Content:
The data is the price history and trading volumes of the 12 stocks in the index NIFTY from the NSE India.All data is at a day-level with pricing and trading values splitted across different tables. The data spans from January 2000 to July 2020.

--------------------+--------+------+-----+---------+-------+
| Field              | Type   | Null | Key | Default | Extra |
+--------------------+--------+------+-----+---------+-------+
| Date               | text   | YES  |     | NULL    |       |
| Symbol             | text   | YES  |     | NULL    |       |
| Series             | text   | YES  |     | NULL    |       |
| Prev Close         | double | YES  |     | NULL    |       |
| Open               | double | YES  |     | NULL    |       |
| High               | double | YES  |     | NULL    |       |
| Low                | double | YES  |     | NULL    |       |
| Last               | double | YES  |     | NULL    |       |
| Close              | double | YES  |     | NULL    |       |
| VWAP               | double | YES  |     | NULL    |       |
| Volume             | int    | YES  |     | NULL    |       |
| Turnover           | double | YES  |     | NULL    |       |
| Trades             | text   | YES  |     | NULL    |       |
| Deliverable Volume | text   | YES  |     | NULL    |       |
| %Deliverble        | text   | YES  |     | NULL    |       |
+--------------------+--------+------+-----+---------+-------

Motivation: 
Stock market data is extensively analysed for business purpose. Various machine learning techniques can be applied and explored to stock market data, especially for trading algorithms and learning time series models.

TASKS TO DO
1) Install any three Databases.
2) Insert three tables each into them from the above stock csv files.
3) SFTP three additional csv files into the LFS.
4) Populate all the Tables from the databases to the HDFS directory.
5) Put the SFTP files from the LFS to the hadoop directory.
6) Finally, create HIVE external tables from these files.

