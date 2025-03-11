# 地質敏感區範圍數值檔(SHP)

[資料來源下載](https://www.gsmma.gov.tw/nss/p/H001d2#)

## 資料處理

資料處理流程描述如下：

1. 使用`Merge`工具合併所下載的Shapefile檔案
2. 開啟`屬性表`刪除不必要的欄位
3. 使用`Calcute Field`彙整不同欄位名稱的資料，例如: `name`欄位與`名稱`欄位應該是相同的欄位資料
4. 參考[Create centerlines from polygons in ArcGIS Pro](https://support.esri.com/en-us/knowledge-base/how-to-create-centerlines-from-polygons-in-arcgis-pro-000022240)這篇文章，對範圍資料取中線，作為斷層線段資料。

