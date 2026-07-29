# 雷蒙三十網站社群討論中心

這個公開 repo 是 `lifehacker-tw` 網站生態共用的 GitHub Discussions 與 [giscus](https://giscus.app/) 留言資料庫。

## 用途

- 集中保存各網站的公開留言與回覆。
- 讓訪客使用 GitHub 帳號留言、reply 與 reaction。
- 提供團隊統一的 moderation 與社群規範。

本 repo 不保存網站原始碼、憑證、學員私密資料或內部文件。

## 留言識別規則

每個網站與頁面使用全域唯一 key：

```text
<site-key>:<content-slug>
```

目前登記：

- 學員作品集：`student-gallery:<work-slug>`

未來新增網站時，必須同時：

1. 登記新的 `site-key`。
2. 將正式 origin 加入 `giscus.json`。
3. 確認不會與既有 Discussion key 衝突。

## 社群規範

請針對作品與內容進行友善、具體的交流。禁止人身攻擊、騷擾、垃圾廣告、釣魚連結，以及公開他人的個人或機密資訊。管理團隊保留隱藏、刪除或鎖定不當內容的權利。
