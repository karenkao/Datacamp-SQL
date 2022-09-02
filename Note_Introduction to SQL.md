# Introduction to SQL

_https://campus.datacamp.com/courses/introduction-to-sql/relational-databases?ex=1_

## ch1 Relational Databases

### Databases

這堂課程的目標: 

1. 電子化儲存 data
2. 使用 sql code 儲存資料，撈取資料

- database vs traditional data stored 

database 的優勢為:

1. 更好的儲存空間比起舊的sheet 存放的方式
2. 儲存更安全，因為加密的關係
3. 可以同時多個 user 使用資料庫進行撈取讀取資料庫訊息

### Tables

表格命名:
  1. 小寫
  2. _ 取代空格
  3. 有意義
  4. field name(表格欄位名稱) 和 table 名稱不能相同

key(類似 id 的概念): 
  1. unique
  2. 通常是數字

key 對於表格的重要性:

可以看下面這張圖，上排兩個表格可以透過 key 串接，合併成為 patron_checkouts 的表格，但 patron_checkouts 的表格其實不好，因為有一些重複、缺值，所以表格拆散是更好的。

  ![image](https://user-images.githubusercontent.com/88547312/187866699-e8eca3ef-1ff9-4045-b4e1-9de5a907b878.png)

### Data

表格的type :

1. INT
2. NUMERIC
3. VARCHAR
4. DATE

可以透過 database schemas 知道欄位的表格有哪些和表格的類型以及表格與表格的關聯，如下圖:
![image](https://user-images.githubusercontent.com/88547312/188092215-5f5751a5-9187-47b8-91f6-a87188c371f9.png)

data storage 除了硬體的資料存放，同時 database 也是一個 server ，可以處理同時多個對資料庫的 requests






