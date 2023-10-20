| 任務 | 說明 | 參與人員 |
|:-------:|:-------:|:------:|
| 1 | 研擬計畫| All |
| 2 | 任務分配 | All |
| 3 | 資料蒐集 | All |
| 4 | 建置資料庫 | All |
| 5 | 前端開發 | All |
| 6 | 後端開發 | All |
| 7 | 程式測試 | All |
| 8 | 撰寫使用者手冊 | All |
| 9 | 使用者訓練 | All |
| 10 | 使用者測試| All |

# 甘特圖
### Mermaid
```mermaid
gantt
    title 工作分解結構
    dateFormat  YYYY-MM-DD
    section 任務1
    研擬任務           : a1,2023-09-25, 1d
    section 任務2
    任務分配           :a2, after a1  , 4d    
    section 任務3
    取得硬體           :a3, after a1  , 17d
    section 任務4
    程式開發           :a4, after a2  , 50d    
    section 任務5
    安裝硬體           :a5, after a3  , 10d    
    section 任務6
    程式測試           :a6, after a4  , 30d   
    section 任務7
    取撰寫使用手冊        :a7, after a5  , 25d
    section 任務8
    轉換檔案           :a8, after a5  , 20d
    section 任務9
    系統測試           :a9, after a6  , 25d
    section 任務10
    使用者訓練         :a10, after a7  , 20d
    section 任務11
    使用者測試         :a11, after a9  , 25d
    
            
```
# PERT 圖
![pert](pert.png "pert")


# 關鍵路徑
關鍵路徑:1->2->4->6->9->11

