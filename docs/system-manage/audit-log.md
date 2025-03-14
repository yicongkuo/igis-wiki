# Audit log

支援版本： 11.4(含)以上

參考文件： [Understand audit logs](https://enterprise.arcgis.com/en/portal/latest/administer/windows/understand-audit-logs.htm)

Audit log在中文稱為`數據軌跡`、`審計軌跡`或`審計日誌`等。在ArcGIS Enterprise中，Portal for ArcGIS 會記錄使用者活動及系統中發生的任何變更，並將這些資訊寫入審計日誌。

審計日誌是監控和排解關鍵或重大變更的重要工具，有助於識別進行變更的組織成員或流程、變更對系統的影響，以及這些事件發生的時間。

審計日誌可以由安全資訊與事件管理（Security Information and Event Management, SIEM）工具處理，生成審計追蹤，追蹤使用者活動的趨勢，並監控和處理任何安全威脅或漏洞。

審計日誌會捕捉以下事件的資訊：

- 訪問組織的入口網站
- 創建、刪除、更新和停用成員帳戶
- 創建和更新使用者角色
- 新增和配置群組
- 新增和移除群組成員
- 分享項目
- 更改項目所有權
- 新增、更新、移動和刪除項目
- 審計日誌存取

# 取得 Audit log

Portal for ArcGIS 預設會將審計日誌寫入 C:\arcgisportal\logs\<機器名稱>\audit 目錄。您可以隨時透過 Portal 管理員目錄來更改審計日誌的位置。

此外，您也可以在 `Portal Administrator Directory` 的路徑 `Home  > Logs  > Export` 下載取得。


