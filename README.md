# 0x-instant-demo

我在 Medium 上寫的教學文章： [0x Instant 實作及深入解析](https://medium.com/@robinpan)

此 Repository 為 0x Instnat 的實作 DEMO，
透過 Github Pages 將購買頁面顯示給使用者

對於不想自己實作 0x Instant 的使用者，透過 DEMO 頁面可以直接看到實作結果，
並且自己嘗試購買我在 Kovan Testnet 上發行的 [RobinToken(ROB)](https://kovan.etherscan.io/address/0xbcbe75079da5cf33d3e7a1712f6547161f46712b) ，
以更瞭解 0x Instant 的運作。(部署在測試鏈，不用擔心要花真錢。連到 [Kovan Faucet](https://github.com/kovan-testnet/faucet#kovan-faucet) 後，頁面中提供兩種方式申請免費 ETH 測試)


範例中傳入 `orderSource` 的值，是用 0x 生成的 `signedOrder` ，
主要內容為販售 "RobinToken(ROB)" ，價格設定為 `1 ROB = 0.0001 ETH`
