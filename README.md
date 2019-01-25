# 0x-instant-demo

我在 Medium 上寫的教學文章： [0x Instant 實作及深入解析](https://medium.com/@robinpan)

此 Repository 為 0x Instnat 的實作 DEMO，
透過 Github Pages 將購買頁面顯示給使用者

對於不想自己實作 0x Instant 的使用者，透過 DEMO 頁面可以直接看到實作結果，
並且自己嘗試購買我在 KOVAN Testnet 上發行的 "RobinToken" (部署在測試鏈，不用擔心要花真錢)，
以更瞭解 0x Instant 的運作。


範例中傳入 `orderSource` 的值，是用 0x 生成的 `signedOrder` ，
主要內容為販售 "RobinToken" ，價格設定為 `1 RobinToken = 0.0001 ETH`
