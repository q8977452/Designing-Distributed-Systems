# Work Queue

## 典型樣貌
![](https://pic3.zhimg.com/v2-b7b5f56848cd8591b937f990f0dfc860_1440w.jpg?source=172ae18b)

## 基本演算法
1. 透過調用來源容器介面載入可用的工作
2. 查詢工作佇列狀態，以確定目前已經處例或正在處理的工作項目
3. 對於這些項目，生成工作容器介面用來處理工作項目的作業
4. 當其中一個工作容器成功完成時，紀錄工作項已完成