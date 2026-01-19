
# 26.01.19


https://blog.elcomsoft.com/2026/01/web-browser-forensics-in-digital-triage/

這一篇有提及一般用 chrome 系列瀏覽器，會用 sqlite 去看有哪些資料，文章裡面有列出主要要看的項目 for 鑑識

---


https://paraben.com/memory-forensics-beyond-the-endpoint-volatile-evidence-in-modern-cloud-and-edge-environments/

這一篇講雲端上做鑑識，裡面給了一些參考連結


---


https://www.team-cymru.com/post/analysing-carding-infrastructure

這一篇是研究信用卡盜刷的 infra
- 找他們常見的 ASN Number 是啥
- 常用的頂級 Domain (TLD) 是 .su , .cc , .ru
- 研究方法
  - 對全網的 port 做掃描
  - 收集 passive DNS 資料
  - 整理 PORT 80 , 443 , 還有各種網頁標題用 Regex 搜尋 (ex: CVV , DUMP 等
  - 針對憑證作搜尋
 

---

https://www.sysdig.com/blog/how-threat-actors-are-using-self-hosted-github-actions-runners-as-backdoors

還沒讀但蠻有趣的，透過 Github action 放後門

