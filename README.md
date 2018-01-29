# Crawler-for-Java

## Community
### ConnectionTools
- [Jsoup](https://jsoup.org/cookbook/introduction/parsing-a-document/)
</br>優點:能支援大部分的方法尤其在Cookie的處理。
</br>缺點:POST時遇到payload格式(聽說最新版本已支援尚未測試...)，不支援ConnctionTimeOut只能統一設定，撰寫PostDate相當的麻煩，JavaScript不支援。
- [HttpURLConnction](https://docs.oracle.com/javase/7/docs/api/java/net/HttpURLConnection.html/)
</br>優點:能夠設定很詳細的連線選項。
</br>缺點:在撰寫上非常的麻煩，JavaScript不支援。
- [WebClient](https://cxf.apache.org/javadoc/latest/org/apache/cxf/jaxrs/client/WebClient.html/)
</br>優點:能夠模擬瀏覽器上的大部分動作，更新很快。
</br>缺點:執行相當的慢，某些功能要等待更新。
- [Selenium](https://wiki.saucelabs.com/display/DOCS/Example+Selenium+Scripts+for+Automated+Website+Tests)
</br>優點:能夠模擬全部瀏覽器的動作，還能夠拿來做自動測試。
</br>缺點:每次執行真實的瀏覽器(有幽靈模擬器不過還是會執行)，使用資源過大。
- [Unirest](http://unirest.io/)
</br>優點:速度快，撰寫相當方便，能夠直接輸出Json格式，傳遞Data相當方便使用(目前主力使用)。
</br>缺點:Cooki支援度不高，JavaScipt不支援，有一項BUG設定一次以上的TimeOut會造成Thread的滯留。
## Parser
- [Jsoup](https://jsoup.org/)
- [Jsoup測試](https://try.jsoup.org/)
</br>在Parser無敵手
</br>1.利用HtmlTag當索引。
</br>2.能夠對Html做修改再輸出。
</br>3.清除Html不需要的資料(XSS攻擊)。
</br>4.選擇器:Tag名稱、命名空間、ID、Class、屬性、屬性前墜、屬性數值、正則表達式，以上所有方法都可以任意搭配組合(利用> + ~ ,)。
</br>5.表達式:小於N列、取得包含N數量以上，取得包含N數量，包含X元素，不包含X，有X內容之容器，完全符合X內容之容器，正則表達式過濾，正則表達式取得。
## ConectionStep
## Example Website
