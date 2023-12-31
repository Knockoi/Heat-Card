# Heat-Card
 
## 語言選擇:
[English](https://github.com/Knockoi/Heat-Card/blob/main/Readme.md) | [简体中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-CN.md) | [繁體中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-TC.md)
  
## 概述
這款迷你加熱台尺寸小巧，方便攜帶，與市面上的MHP30迷你加熱台相比，它擁有更大的加熱面積，不再受限於小小的加熱區域，機身更薄，可輕鬆放入口袋中。此外，它採用特別設計的PCB和銅柱組合，每一層功能都可以客製化設置，操作界面簡潔明了，使用簡單的RGB燈顯示狀態，其他設置可以通過藍芽連接手機或電腦進行調整，並支持藍芽和USB進行韌體升級，保證了機器的不斷改進和更新。
  ![image](https://github.com/Knockoi/Heat-Card/blob/main/Image/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202023-10-22%20183807.png)
  
 ## 硬體   
- MCU使用ESP32 C3
- MOSFET使用NCEP40T11G控制熱板溫度
- 溫度測量使用PT1000 
- 支持USB傳輸資料和UART傳輸資料(USB)
- 三向按鈕來選擇模式
- RGB顯示模式及系統資訊
   
 ## 功能  
- 仿回流焊接。
- 恆溫加熱(1) 100~°C。
- 恆溫加熱(2) 200~°C。
- 恆溫加熱(3) 300°C。
- 快速回流焊接 時間是仿回流焊接的2/3。
  
 ## 按鍵功能  
 - 左鍵 左滑開關選單向左滑。
 - 右鍵 右滑開關選單向右滑。
 - 中鍵按住<=3S 確定。
 - 中鍵按住>=5S 藍牙重新連接。
 - BOOT鍵 下載按鈕。按住Boot，然後按Reset可啟動韌體下載模式，透過序列埠下載韌體。
 - RESET鍵 按此按鈕重新啟動系統。
  
 基本按鍵可以參考ESP32-C3-DevKitM-1的使用方法。

     
   

