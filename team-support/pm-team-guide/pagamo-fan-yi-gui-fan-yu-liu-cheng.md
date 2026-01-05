# PaGamO 翻譯規範與流程

## Overview

* 翻譯檔案與使用說明
* 中英翻譯格式須知：說明 PaGamO 內部中英文翻譯的一致性標準與格式須知。([Link](pagamo-fan-yi-gui-fan-yu-liu-cheng.md#zhong-ying-fan-yi-ge-shi-xu-zhi))
* AI 翻譯工具說明：提供 AI 翻譯工具的操作方式，協助翻譯流程更高效。([Link](pagamo-fan-yi-gui-fan-yu-liu-cheng.md#ai-fan-yi-gong-ju-shuo-ming))
* 參考資源 ([Link](pagamo-fan-yi-gui-fan-yu-liu-cheng.md#can-kao-zi-yuan))



***

## 翻譯檔案與使用說明



1.  **翻譯流程說明**

    1. PM&#x20;
       1. 每個 SP 請於檔案最上方插入下一個 Sprint 需要翻譯的內容，並依據欄位填寫完整資訊，包含要翻譯的內容、文案的屬性(標題/按鈕)、負責PM 以及相關的 Redmine票
       2. 需要翻譯的內容請最晚在每個Sprint 第二個週五下班前貼上，工讀生會在每個Sprint 開始前，協助檢核並修正 AI 翻譯的內容
       3. 複製翻譯的儲存格連結，貼到 Redmine 票上的 translation 欄位，以便 RD 快速找到對應的翻譯文案
       4. 如果覺得較常用的名詞、句型，可以自行新增至 FixedPhases (固定句型) 、常用名詞 (Glossary)&#x20;
    2. 工讀生
       1. 主要使用翻譯檔案
       2. 將 AI 函式套用到需要翻譯的內容，及對應的語言
       3. 參考翻譯檔案的『[檢查清單](https://docs.google.com/spreadsheets/d/1Fttp_cc20PW4_9CEMu-x92g_yj6FktOTr0OGg4WR_Sc/edit?gid=564200372#gid=564200372\&range=A1:B2)』，檢核 AI 翻譯的結果


2. **翻譯檔案連結**：[Link](https://docs.google.com/spreadsheets/d/1Fttp_cc20PW4_9CEMu-x92g_yj6FktOTr0OGg4WR_Sc/edit?gid=1443460916#gid=1443460916)

* 新版檔案搬移至 google sheet，透過 AI 來提高翻譯效率
* 請使用 PM 或 RD 共用帳號進入使用
  * pm\_team@g.bonio.com.tw
  * rd\_team@g.bonio.com.tw
* 從 2025.10 開始使用 (SP266)



3. **舊版翻譯檔案**：[Link](https://boniotw-my.sharepoint.com/:x:/r/personal/bonio_share_bonio_com_tw/_layouts/15/Doc.aspx?sourcedoc=%7BD90825E4-63D0-4CB2-966E-1CEC607AC2BA%7D\&file=%E7%BF%BB%E8%AD%AF.xlsx\&action=default\&mobileredirect=true)
   1. 使用至 2025.09 (SP265)



***

## 中英翻譯格式須知

### 翻譯規則：

1. 此段落說明 PaGamO 在中英文翻譯時需遵照的格式
2. 表格中的「自動修正」是指檢查到對應的文字格式時，系統端會自動將文字內容修正成正確的格式



### 中英文字混合排版：&#x20;

<table data-header-hidden><thead><tr><th width="99"></th><th width="236"></th><th width="230"></th><th width="70"></th><th></th></tr></thead><tbody><tr><td><strong>編號</strong> </td><td><strong>規則</strong> </td><td><strong>示範</strong> </td><td><strong>自動修正</strong> </td><td><strong>備註</strong> </td></tr><tr><td>1 </td><td>中英文字相連，中間要有一個半形空格 </td><td>歡迎來到 PaGamO 國小天地 </td><td> O</td><td> </td></tr><tr><td>2 </td><td>中英混合句，都採用全型標點符號，但在英文句子中，則採用半形標點符號 </td><td><ul><li>「PaGamO」教育遊戲第一名 </li><li>馬克思說，哲學家以不同的方式解讀世界，但世界需要的不是解讀，而是改變（The philosophers have only interpreted the world, in various ways: the point, however, is to change it）。 </li></ul></td><td>X</td><td>應該可以，確認看看 </td></tr><tr><td>3 </td><td>結尾是全形標點符號，下段英文不需要空格 </td><td>國小天地，PaGamO 最受歡迎世界 </td><td>O</td><td> </td></tr><tr><td>4 </td><td>結尾英文遇到下段中文，要使用全形標點符號 </td><td>Walcome to PaGamO，教育遊戲第一名 </td><td>X</td><td>應該可以，確認看看 </td></tr></tbody></table>



### 純英文排版：&#x20;

<table data-header-hidden><thead><tr><th width="91"></th><th width="252"></th><th width="227"></th><th width="67"></th><th></th></tr></thead><tbody><tr><td><strong>編號</strong> </td><td><strong>規則</strong> </td><td><strong>示範</strong> </td><td><strong>自動修正</strong> </td><td><strong>備註</strong> </td></tr><tr><td>1 </td><td>英文跟英文之間要有一個半形空格 </td><td>Welcome to PaGamO Global </td><td> X</td><td></td></tr><tr><td>2 </td><td>標點符號（逗號、冒號、句號）前面不要空格，後面要有一個半形空格 </td><td><ul><li>This study will examine four major factors: interest rates, financial structure, management issues, and systematic processes. </li></ul><p> </p></td><td> X</td><td> </td></tr><tr><td>3 </td><td>標點符號（逗號、冒號、句號）需要緊跟在方括號或圓括號後面，不留空格。 </td><td><ul><li>This study will examine four major factors (Nomen, 2015): interest rates, financial structure, management issues, and systematic processes. </li></ul></td><td>X</td><td></td></tr><tr><td>4 </td><td>按鈕的英文首字母都大寫，特定詞才小寫 </td><td>Send to My Boss </td><td> X</td><td>介系詞、連接詞等 </td></tr><tr><td>5 </td><td>英文一律使用半形符號 </td><td> </td><td>X </td><td> </td></tr></tbody></table>



### 有數字、特殊符號的排版議題：

<table data-header-hidden><thead><tr><th width="88"></th><th width="275"></th><th width="209"></th><th width="67"></th><th></th></tr></thead><tbody><tr><td>編<strong>號</strong> </td><td>規<strong>則</strong> </td><td><strong>示範</strong> </td><td>自<strong>動修正</strong> </td><td>備註 </td></tr><tr><td>1 </td><td>數字與英文相接，中間要有一個半形空格 </td><td>PaGamO 13 anniversary </td><td> X</td><td> </td></tr><tr><td>2 </td><td>數字與中文相接，中間要有一個半形空格 </td><td>歡迎來到 13 週年都加入遊戲 </td><td>O </td><td> </td></tr><tr><td> </td><td>在數字與任何單位之間通常都需要留一個空格，表示角度單位的度（°）除外。 </td><td> </td><td>X </td><td> </td></tr><tr><td>3 </td><td>數字後面接英文單位時，不空格 </td><td>10mins </td><td>O </td><td> </td></tr><tr><td>4 </td><td>數字後面接中文單位時，中間要有一個半形空格 </td><td>10 分鐘 </td><td>O</td><td>補 </td></tr><tr><td>5 </td><td>符號後面是英文時，不空格 </td><td>#PaGamO</td><td>O </td><td> </td></tr><tr><td>6 </td><td>符號後面是中文時，不空格 </td><td>#教育遊戲首選 </td><td>O </td><td> </td></tr><tr><td>7 </td><td><p>英文句子中有 "-" 前後不需要加空格 </p><ul><li>Dash（連接號）/Hyphen（連字號） </li></ul></td><td><ul><li>8-3.3、July 1-December 31、ages 65-75 </li><li>Taipei-Tokyo flight </li><li>word-of-mouth </li></ul></td><td>X </td><td> </td></tr><tr><td>8 </td><td>中文文稿一律使用教育部《重訂標點符號手冊》中所訂之全形標點符號 </td><td>句號「。」、逗號「，」、頓號「、」、分號「；」、冒號「：」、問號「？」、驚嘆號「！」、單引號「」、雙引號『』、括號（）、破折號「──」、刪節號「……」、音界號「‧」、書名號「《》」、篇名號「〈〉」。破折號與刪節號一律佔兩格全形字元，其餘標點符號均佔一格；書名與篇名連用時，可省略篇名號。 </td><td>X </td><td> </td></tr><tr><td>9 </td><td>引號用於標示說話、引語、特別指稱或強調的詞語。先單引號，再雙引號。 </td><td>老師說：「你們要記住國父說的『青年要立志做大事，不要做大官』這句話。」 </td><td>X </td><td> </td></tr><tr><td>10 </td><td>中文用到括號（）時，用於行文中需要注釋或補充說明，前後符號各占一個字的位置，居正中。前半不出現在一行之末，後半不出現在一行之首。 </td><td>蘇軾，字子瞻，號東坡居士，宋眉山（今四 川省 眉山縣）人。</td><td>X </td><td><p></p><p> </p></td></tr><tr><td>11 </td><td>英文單雙引號 '', "" 的用法 </td><td><p>美式英文：Angela had the nerve to tell me “When I saw ‘BYOB’ on your invitation, I assumed it meant ‘Bring Your Old Boyfriend.’” </p><p>英式英文： ' "a" '，剛好跟美式英文相反 </p></td><td>X </td><td>採用美式英文？ </td></tr></tbody></table>





***

## AI 翻譯工具說明

### 一、使用方式

1. 在英文、簡體中文的儲存格中輸入： TranslateCell("要翻譯的繁體中文儲存格", "目標語言", "屬性")&#x20;
   1. 參數1: 請指定你要翻譯內容的所在欄位（繁體中文）&#x20;
   2. 目標語言：英文( "en" ), 簡體中文 ( "zh-CN" )&#x20;
   3. 屬性：“標題”, "按鈕" ; 若為一般內文，則可以直接留白
   4. 使用範例：&#x20;
      1. 函式（英文）：“=TranslateCell($C5,"en",$A5)”&#x20;
      2. 函式（簡體中文）：“=TranslateCell($C5,"zh-CN",$A5)”
2. 將函式翻譯後的儲存格複製，並僅貼上值，只貼上純文字的內容方便編修，未來翻譯內容也才不會一直動態改變。
3. 取得純文字後，再進行人工審核與調整。



### 二、使用注意事項

1. 請留意中英文內容是否缺少標點符號，例如：沒有句號
2. 固定句型請更新至 FixedPhrases，慣用字請記得更新到Glossary，包含像是地形名稱等，未來可能會再次用到的翻譯，就記得更新
3.  固定句型的檢查&#x20;

    1. 要留意標點符號正確及完整，不然可能會比對失敗，而由AI 重新做翻譯。&#x20;

    例如，以下缺乏句號的文案，就會比對失敗：

    『將\_\_\_\_升級為\_\_\_\_，土地血量高，無法放置怪獸。』

    『將\_\_\_\_升級為\_\_\_\_，土地血量高，無法放置怪獸』<br>

    1. 有時候太大量翻譯還是會失敗，如果確認繁體中文無誤，可以刪掉該儲存格，重新貼上一次公式。
4. 內容比較長、包含諧音梗或是專有名詞，AI 翻譯上比較困難，再請記得多檢查一次。
5. 目前屬性有標記成『標題』、『按鈕』，會做格式檢查，若是一般句子就不需要特別標記。



### 三、翻譯規則與 AI 處理邏輯說明



1. **標點符號**

* 英文：逗號、句號需緊接在前方字詞後，後方加一個空格，不可留空格在前。&#x20;
* 中文：使用全形標點，刪除多餘的半形符號。&#x20;
* 中英文混合：自動在中文與英文之間補一格空白。&#x20;
* 冒號（:）、驚嘆號（!）、句號（.）在英文中統一使用半形。



2. **中英文結構**

* 中文標點換成英文標點時會做正確轉換，不會消失或多加。&#x20;
* 英文標題使用標題式大小寫 (Title Case)，且依規則省略結尾句號。



3. **屬性判斷**&#x20;

* 標題：翻譯時採 Title Case，不加句號。&#x20;
* 按鈕：保持簡潔，用 Title Case，不加標點，動詞保持原型。&#x20;
* 項目/用法：簡短明確，避免冗長。&#x20;
* 道具名稱 (item)：需符合 Glossary，長度不可超過 26 半形字元，專有名詞首字母大寫。&#x20;
* 無屬性標註的，則視為一般文字段落，正常翻譯並保留句尾句號。



4. **固定句型與 Glossary**&#x20;

* 有固定句型時，會先比對並套用模板，避免留下「\_\_\_\_」。&#x20;
* Glossary（詞彙表）先行替換，確保專有名詞一致，如「草原 → Meadow」「早餐車 → Breakfast Cart」。



5. **繁簡轉換**&#x20;

* 繁體 → 英文：透過 Gemini 翻譯。
* 繁體 → 簡體：透過轉換函式直接處理，不依賴 AI，避免遺漏或字數截斷。



6. **長度與一致性**&#x20;

* 翻譯時自動檢查字數限制（道具名稱 ≤ 26 半形字元）。&#x20;





***

## 參考資源：

1. 設計概念：
   1. [多語系 產品在設計時該考慮什麼，才能有好的使用者體驗？｜設計大舌頭 (designtongue.me)](https://designtongue.me/ux-design-for-internationalization/)&#x20;
2. 中文規範來源：&#x20;
   1. [清華大學論文寫作要點](http://thup.site.nthu.edu.tw/p/412-1210-9517.php?Lang=zh-tw)&#x20;
   2. [教育部國語推行委員會編著，《重訂標點符號手冊》修訂版](https://language.moe.gov.tw/001/upload/files/site_content/m0001/hau/c2.htm)&#x20;
3. 工具：&#x20;
   1. 前端檢查工具：[https://github.com/huacnlee/autocorrect](https://github.com/huacnlee/autocorrect)&#x20;
   2. 感覺好用的音節斷字：[Hyphnes- CSS: CAscading Style sheets](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens#suggesting_line_break_opportunities)&#x20;
4. 英文規範來源：&#x20;
   1. 專業翻譯社針對英文寫作的 &#x20;
      1. [WORDVICE](https://blog.wordvice.com.tw/%E5%AD%B8%E8%A1%93%E8%AB%96%E6%96%87%E5%AF%AB%E4%BD%9C%E4%B8%AD%E5%B8%B8%E8%A6%8B%E7%9A%84%E9%8C%AF%E8%AA%A4%EF%BC%9A%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F/)&#x20;
      2. [華樂絲學術英文編修](https://www.editing.tw/blog/%E4%BB%8B%E7%B4%B9%E8%8B%B1%E6%96%87%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F%E5%8F%8A%E6%AD%A3%E7%A2%BA%E7%94%A8%E6%B3%95.html)&#x20;





