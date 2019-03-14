# 107-2 金融科技-文字探勘與機器學習

R06723020 財金碩二 楊安祺

## Home work 01

### Description

**ETF crawler**  

1. read excel files for the list of ETFs, get symbol, ETF name and asset class    
2. use symbols to crawl etfdb.com and get info of issuer and link of fund homepage    
3. combine dataframe and write to excel   
4. crawl historical NAV data from fund home page -> partially finished:**"ProShares"**

### Problems to follow up    

* etfdb.com 可能有反爬蟲機制，短時間爬太多資料就卡住，目前先用延遲3秒的方式...討論如何優化
- Issuer為"AGFiQ Asset Management" 時 etfdb.com 給的 Homepage 找不到網頁....

