# Air-Voltage-Signals

包含多個地震預測站的空氣電壓訊號數據，用於地震預測。  

資料夾結構：  
- Yilan_Station：宜蘭站  
  - 20250430_162700：2025-04-30 16:27:07 至 2025-05-12 19:21:45，紫色訊號、紅色訊號（W 形，3600 mV）  
- Zhejiang_Station：浙江站  
- SanFrancisco_Station：美國舊金山站
    
每個資料夾包含：  
- Voltage.tdms：原始數據，與 .seproj 搭配使用於 NI Signal Express  
- *.seproj：NI Signal Express 專案檔  
- Voltage.txt：轉換後文字檔（單位 mV）  
- Voltage_meta.txt：元數據
