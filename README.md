# API

爬行 API 時，可利用 JS 和 Ajax 直接從資料源 Open Data Resource 抓取，即利用產生資料的 API。
API 文件說明請求的 URL 端點 (訪問的目標)與放在 URL 或 GET 方法的參數。

範例：

      http:qspie.com/api-route/path-param
 
傳遞變數資料方法，以路徑或參數來傳遞

      http://qspies.com/api-route?paramVal001=path-param
      
改變參數，請求其他格式的回應

      http://freegeoip.net/csv/50.78.253.58
      
回傳格式

* JSON

          {"user":{"id": 001, "name": "queen", "city": "TPE"}}

* XML
      
          <user>
             <id>001</id>
             <name>queen</name>
             <city>TPE</city>
          </user>


