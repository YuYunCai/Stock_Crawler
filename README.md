# 股票爬蟲程式使用說明書📈

## 摘要

歡迎使用這個功能豐富的股市每日抓取程式碼。這個程式碼能夠輕鬆地抓取每日股市數據，將市場資訊直接呈現在您的手中。無論您的投資經驗如何，這個程式碼都能夠成為您的得力助手，協助您做出更為明智的投資決策。

## 功能特點

- 使用 Python 的 xml.etree.ElementTree 和 requests 函式庫，能夠輕鬆讀取 XML 格式的股市數據並轉換為字典。
- 利用 openpyxl 函式庫，方便將數據保存為 Excel 檔案，以供後續分析和查看。
- 提供函式如 xml_to_dict 和 fillSheet，使數據處理更加便捷。

## 如何使用

1. 下載exe檔案以及xml檔案。
2. 打開xml檔案，輸入以下相關資訊：
   - 股票代碼(stockNo)
   - 查詢時間範圍(startYear、startMonth、EndYear、EndMonth)
   - 輸出的Excel檔案名稱(excelName)
3. 存檔並關閉xml檔案。

## 執行程式碼

執行exe檔案，程式碼將自動從指定的網址獲取股市數據，並將其整理保存至指定的Excel檔案中。

## 注意事項

- 程式碼已考慮股市數據的更新頻率和API的使用限制，使用延遲等待時間以避免對API服務器造成過大的負荷，同時確保您能夠獲取到最新的數據。

## 提升投資效益

利用這個程式碼，您可以根據自己的需求定制抓取股市數據的時間範圍，從而獲得特定期間內的股票價格、成交量、漲跌幅等重要指標。這些數據可用於技術分析、趨勢預測和投資策略制定，有助於提升您的投資效益。

## 結語

這個股市每日抓取程式碼將為您帶來更便捷的股市數據獲取方式，讓您更好地了解市場動態和股票表現。無論您是個人投資者還是機構投資者，這個程式碼都能夠提供寶貴的支持和指導，讓您在投資之路上更加成功和有成效。

立即體驗這個強大的功能吧！下載並運行程式碼，開始獲取每日股市數據，為您的投資決策提供更可靠的依據。祝您在股市投資中取得卓越的成果！
