# 冷藏配送據點地圖 Demo

以 Leaflet 製作的配送據點地圖（作品集展示用，所有地點與資料皆為虛構）。

- 自動定位、MarkerCluster 群聚標記
- 「配送到府」點顯示 1 公里服務範圍，「定點取貨」點附 Google Maps 導航
- 資料來源為 CSV（`data/points.csv`），可替換為任何 Google Sheets 發佈的 CSV

技術：HTML / Bootstrap 5 / Leaflet / PapaParse / SweetAlert2

## 本地執行

```bash
python3 -m http.server 8000
# 開啟 http://localhost:8000
```
