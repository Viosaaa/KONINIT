# 股票每日成交統計報告生成程式

這個程式使用 Python 語言開發，旨在根據指定的股票代號和時間範圍，自動爬取每日成交資訊，將數據整理後儲存到 Excel 檔案中，以生成股票每日成交統計報告。您已經將主程式碼轉換成可執行文件（exe），使得程式更方便運行。

## 使用方法

1. 將主程式碼轉換成的可執行文件放置於您想要的目錄中。
2. 創建一個名為 `setting.xml` 的 XML 設定檔，指定爬取參數，包括起始年月、結束年月、股票代號、爬取網址等。以下是一個範例 `setting.xml` 設定內容：

   ```xml
   <params>
       <url>https://www.twse.com.tw/rwd/zh/afterTrading/STOCK_DAY</url>
       <excelName>巨大</excelName>
       <startYear>2023</startYear>
       <startMonth>01</startMonth>
       <endYear>2023</endYear>
       <endMonth>08</endMonth>
       <stockNo>9921</stockNo>
   </params>
   ```

執行轉換成的可執行文件，程式將根據 setting.xml 的參數，自動爬取股票每日成交資訊，並生成 Excel 表格報告。
# 注意事項
請確保 setting.xml 的格式正確且參數設置正確。
請遵守網站爬取的法律和道德準則，避免不正當的爬取行為。
# 環境要求
Windows 作業系統
# 聯絡方式
如有任何疑問或建議，請聯絡作者：[您的名字]（您的電子郵件地址）。

# 授權許可
此程式採用 MIT 授權。

免責聲明： 本程式僅供學習和測試用途，使用時請遵守相關法律法規，尊重網站規定，不得用於商業目的。
