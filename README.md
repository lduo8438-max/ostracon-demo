# ostracon-demo

[Ostracon](https://github.com/lduo8438-max/ostracon) 的線上 demo。

**這個 repo 裡全部是產生檔**，由 `ostracon export` 從索引匯出：

```bash
ostracon export --db <index.db> --out <dir> --label <語料名稱>
```

之所以與主 repo 分開，是為了不讓想安裝這個工具的人多下載這 38 MB
——安裝摩擦是開源專案的頭號死因。

三個語料各自釘在固定的 commit，是快照不是即時服務。

## 這支 GIF

`ostracon-w4.gif`（10 秒）走過一遍：全部宣告 → 被推翻的做法 → 篩選 → 挑一條
看它的時間軸與意圖。畫面上的數字與各語料的 `api/summary.json` 同源。
