# API

爬行 API 時，可利用 JS 和 Ajax 直接從資料源 Open Data Resource 抓取，即利用產生資料的 API。
API 文件說明請求的 URL 端點 (訪問的目標)與放在 URL 或 GET 方法的參數。

# Route & Param, passing data

範例：

      http:qspie.com/api-route/path-param
 
傳遞變數資料方法，以路徑或參數來傳遞

      http://qspies.com/api-route?param5=path-param-val
      
改變參數，請求其他格式的回應

      http://freegeoip.net/csv/50.78.253.58
      
# Format in Rerurn Result
      
回傳格式

* JSON

          {"user":{"id": 001, "name": "queen", "city": "TPE"}}

* XML
      
          <user>
             <id>001</id>
             <name>queen</name>
             <city>TPE</city>
          </user>
          
* CSV

* PDF

# HTTP methods

常見到 API 以 Get 方法向伺服器請求資料，透過 HTTP 向伺服器請求資訊的方法，如下主要四種方法：

* GET 唯讀, read only.

* POST 建構新實體, write & login to store data in the DB of Server Side.

* PUT 更新已有實體, rewite data such as email addr.

       http://queenspie.com/comments?post=00015

* DELETE 刪除已有實體根據id, rarely used, only in delete the comment in Blog via 

       https://fb.com/use/<userID>/comment/<commentID>

# Request Body

{"title": "this is request from Queen", 
 "body": "(obmit)",
 "attach": {
   "book": "Python Program",
   "url": "https://QueensPy.com.tw",
   "team": "Pattys-i-Chip"
  }
 }
 
# API Doc

發文成功囉！

        {"success": true} # Bool

好像發生了某錯誤喔～

        {"error":{"msg": "you got an error in this phase."}}
 

