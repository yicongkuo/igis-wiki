---
title: File Based
icon: material/file-sign
---

# 以檔案為中心的階段

!!! warning "關注點"
    GIS發展初期， **如何將真實世界的現象與事件正確地記錄下來，並且讓資訊系統能順暢地使用這些記錄** 是GIS的發展重心。

在這個階段，ArcGIS團隊發展出功能強大的桌上型系列軟體 **ArcGIS Desktop**。使用者可以在個人電腦上使用ArcGIS Desktop，輕鬆地進行地圖繪製、地理資料建模、空間分析等作業。隨著技術的演進 [ArcGIS Desktop 即將退休](https://www.esri.com/en-us/arcgis/products/arcgis-desktop/overview)，取而代之的是新世代GIS軟體[ ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)。

**ArcGIS Pro** 可以整合來多種來源的資料、在一個介面中同時查看2D和3D資料，還能將地圖和分析結果發佈為web服務，是一款功能強大的桌上型GIS軟體。

除了軟體外，在這個階段ArcGIS團隊也發展出許多重要的空間資料儲存格式，例如市面上最廣為流傳的 Shapefile , 或是可以同時儲存點、線、面幾何圖形，以及圖形之間上下或交錯等空間關係的`File Geodatabase`，都是以檔案的形式，提供給GIS軟體使用。

近年來隨著網路蓬勃發展，為了方便地理資料在網路上進行交換，Google公司發展出 **`kml`** 格式，GIS社群也發展出 **`GeoJSON`** 、 **`TopoJSON`** 等格式，這些格式都是以文字檔案的形式在網路上進行流通。由此可知，檔案形式是地理資料交換流通的基礎。

有了上述的基礎後，接下來我們將開始了解什麼是地理資訊系統、地理資料，以及如何使用ArcGIS Pro操作各式的地理資料。