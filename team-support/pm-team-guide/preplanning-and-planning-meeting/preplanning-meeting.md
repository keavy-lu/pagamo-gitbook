# Pre-planning 會議

### 會議目的： <a href="#hui-yi-mu-di" id="hui-yi-mu-di"></a>

1. 確保下 Sprint 的開發內容是具體可執行，可讓團隊估算與分解項目
2. 確保下 Sprint 的開發內容具有優先級排序，可讓團隊辨識項目的重要性

### 主持人工作： <a href="#zhu-chi-ren-gong-zuo" id="zhu-chi-ren-gong-zuo"></a>

#### 會議前準備： <a href="#hui-yi-qian-zhun-bei" id="hui-yi-qian-zhun-bei"></a>

1. 於 Sprint W2D2 在 [01\_Sprint\_Planning\_worksheet](https://boniotw-my.sharepoint.com/personal/bonio_share_bonio_com_tw/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fbonio%5Fshare%5Fbonio%5Fcom%5Ftw%2FDocuments%2FPaGamO%2FPM%20Team%2F04%5FSCRUM%E9%96%8B%E7%99%BC%E6%B5%81%E7%A8%8B%2F01%5FSprint%5FPlanning%5FWorksheet\&view=0) 複製當 Sprint sheet 來創建下 Sprint 的 sheet。檔名規則為 SprintXXX\_起始年月日-結束年月日
2. 創建後調整 Sprint sheet 的分頁內容：
   1. checklist分頁：移除內容，並更新成正確的更新日時間（一般正常為Sprint 結束後的下個週二）
   2. OP/DA/Design 分頁：新增新的 Sprint 名稱（直接參考檔案內的寫法）
   3. WebGame/App分頁：等待 pre-planning 再調整即可
3. Sprint W2D2 在 [pagamo\_team](https://bonio.slack.com/archives/C64K2862V) 會有自動化訊息提醒大家會議時間([參考](https://bonio.slack.com/archives/C64K2862V/p1760407208033189))，如果會議時間有改變或訊息失效，請自行發訊息提醒大家。在此訊息之下請更新 sprint sheet 的連結出來給大家（[範例](https://bonio.slack.com/archives/C64K2862V/p1760408999087459?thread_ts=1760407208.033189\&cid=C64K2862V)）。
4. 於 Sprint W2D5 在 [pagamo\_team](https://bonio.slack.com/archives/C64K2862V) 發訊息提醒大家會議時程，範例：[Link](https://bonio.slack.com/archives/C64K2862V/p1718865499447959)​

#### 會議前半段（OP/DA/Design 票審核）： <a href="#hui-yi-qian-ban-duan-opdadesign-piao-shen-he" id="hui-yi-qian-ban-duan-opdadesign-piao-shen-he"></a>

1. 會議時程：
   1. 前 10 分鐘為 OP/DA 票，後續就直接進入設計環節（記得請設計 leader 加入）。
2. 準時開始，先檢視 OP/DA 票的內容（ K12 的票通常統一由 Ben 處理，其餘部門通常開票者會出現）
   1. OP票審核須知：
      1. 確認 due date（注意檔案提供日期要小於 due date 3 個工作日），以及是否有相關票（關聯票 or 母票），如屬於 Sprint 第一週就要完成的票也統一標示為 High 票
      2. 如果是全新的 OP 先確認是否有在相關頻道討論過，且跟其他 PM 確認是否有問題
      3. 如果有疑慮的票則請在備註標示，並附上後續說明，參考：Miles：這張票跟運營重新確認，預計下週二修正完成
   2. DA 票審核須知：
      1. 確認票是否有跟 DA 討論過，如屬於 Sprint 第一週就要完成的票也統一標示為 High 票
      2. 如未跟 DA 論的票，先請開票者跟 James 訊息說明或掛診所，再交由 DA 於 Planning 會議時估是否執行
   3. 結束 OP/DA 票後，沒有要討論設計/PM 票的夥伴就可以請他們先離開，並確認設計昱雯加入會議後就可開始（一般都是會議開始後 10 分鐘開始討論設計票）
   4. MK/BD/Yory設計票審核須知：
      1. 大約從 5 個 Sprint 前開始討論（如不確定可詢問昱雯）
      2. 完成的票，確認後直接刪除掉
      3. 如未完成的票，就協助更新最新狀態在Comment欄位，或移動至正確的 Sprint 位置
      4. MK/BD設計票，通常設計Sprint W2D3 基本都有對完，所以就依據昱雯這邊的資訊調整排序即可
      5. 最後檢查整體分 Graphic/UI Feature 並確認大家都排序都沒有問題後：
         1. 如有 High 票提醒 MK/BD 記得改 high 票
      6. 確認無誤就可請 MK/BD夥伴先行離開，繼續往下執行
   5. PM 設計票審核須知：
      1. 完成的票，確認後直接刪除掉
      2. 如未完成的票，就協助更新最新狀態在Comment欄位，或移動至正確的 Sprint 位置
      3. 每張票的內容均需請 PM 說明，也確認設計清楚理解
      4. 如是預排會議票，當下也先與設計確認合適的會議時間與人選
      5. 最終確認 PM 各個專案的開發時程，確認設計時程可以配合（如 handoff 可以壓上實際完成日，舉例：W2D2）

#### 會議後半段（WebGame/App 票）： <a href="#hui-yi-hou-ban-duan-webgameapp-piao" id="hui-yi-hou-ban-duan-webgameapp-piao"></a>

1. 移票，確認要上線或已完成但無法測試的項目，這些移動到相對應的 sheet
2. 確認「完成但PM還無法測試」有沒有項目要搬到 checklist
3. 引導討論新 sprint 的票， PM 共同查看內容是否完整
   1. 提醒大家 PRD 討論也要列出來
4. comment 更新狀態（開發進度）
5. 確認 High 票，引導討論各票的優先順序，並協助排序
6. 檢視是否有前後端同時開始的票（如需同步進行，應先跟前後端確認）
7. 提醒大家：下 sprint 會轉 high 的 normal 票在票中提醒
8. 確認各 sheet 內容的正確性

*   會議後

    * 調整 checklist 以符合欄位說明，如有 RD 自行開立的子票，字體顏色就標示為灰色且將測試 PM 改為 --。參考：



    <figure><img src="https://images.gitbook.com/__img/dpr=2,width=1168,onerror=redirect,format=auto,signature=-692059648/https%3A%2F%2Fcontent.gitbook.com%2Fcontent%2FipqzI35peegGVmnGWhuh%2Fblobs%2FTETxayfSzKqkHCahqPH3%2Fimage.png" alt=""><figcaption></figcaption></figure>
