

# UML
> 類別圖 (Class Diagram)

> 名詞
1. E-R Model entity-relationship model
2. 觸發程式 trigger / 內儲程式 stored procedure
3. CRC class responsibility and collaboration card (指定類別的責任時，最常用的工具)
4. 限定元 classifier
5. 塑造系統語彙 vocabulary

> 表示法
1. 界面：像棒棒糖的圖形

> 重點
1. 「類別圖」能表示類別(class)、合作(collaboration)、介面(interface)
2. 「類別圖」是「元件圖」、「部署圖」的基礎
3. 使用類別來進行抽象化
4. 可以利用 CRC 卡或者是案例分析的方式，來幫助使用者或系統開發者進行系統的抽象化
5. 針對每一個類別的責任，提供它們所需的屬性與操作
6. 定義抽象類別、實作類別。定義各類別間的關系(一對多、一對一、多對多)
7. 介面：是一組操作的集合。不包含屬性也不包含可供操作的方式。
8. 資料型別、靜態型別、動態型別
9. 信號
10. 類別種類：
```
(1) 抽象化類別 generalized abstraction 
(2) 特殊化類別 specific abstraction -> 以斜體表示
(3) 實體化類別 
(4) 葉類別 leaf class : 這個類別下，沒有子類別。會在類別名稱下方加註一個{leaf}做為標示
(5) 根類別 root class：一個沒有父類別的類別。會在類別名稱下方加註一個{root}做為標示
(6) 只要是在子類別中的行為就可以取代父類別的行為
``` 

