# PaGamO 翻譯規範與流程

\
中英翻譯格式須知翻譯規則：此段落說明 PaGamO 在中英文翻譯時需遵照的格式表格中的「自動修正」是指檢查到對應的文字格式時，系統端會自動將文字內容修正成正確的格式中英文字混合排版：編號規則示範自動修正備註1中英文字相連，中間要有一個半形空格歡迎來到 PaGamO 國小天地O2中英混合句，都採用全型標點符號，但在英文句子中，則採用半形標點符號「PaGamO」教育遊戲第一名馬克思說，哲學家以不同的方式解讀世界，但世界需要的不是解讀，而是改變（The philosophers have only interpreted the world, in various ways: the point, however, is to change it）。X應該可以，確認看看3結尾是全形標點符號，下段英文不需要空格國小天地，PaGamO 最受歡迎世界O4結尾英文遇到下段中文，要使用全形標點符號Walcome to PaGamO，教育遊戲第一名X應該可以，確認看看純英文排版：編號規則示範自動修正備註1英文跟英文之間要有一個半形空格Welcome to PaGamO GlobalX2標點符號（逗號、冒號、句號）前面不要空格，後面要有一個半形空格This study will examine four major factors: interest rates, financial structure, management issues, and systematic processes.X3標點符號（逗號、冒號、句號）需要緊跟在方括號或圓括號後面，不留空格。This study will examine four major factors (Nomen, 2015): interest rates, financial structure, management issues, and systematic processes.X4按鈕的英文首字母都大寫，特定詞才小寫Send to My BossX介系詞、連接詞等5英文一律使用半形符號X有數字、特殊符號的排版議題：編號規則示範自動修正備註1數字與英文相接，中間要有一個半形空格PaGamO 13 anniversaryX2數字與中文相接，中間要有一個半形空格歡迎來到 13 週年都加入遊戲O在數字與任何單位之間通常都需要留一個空格，表示角度單位的度（°）除外。X3數字後面接英文單位時，不空格10minsO4數字後面接中文單位時，中間要有一個半形空格10 分鐘O補5符號後面是英文時，不空格#PaGamOO6符號後面是中文時，不空格#教育遊戲首選O7英文句子中有 "-" 前後不需要加空格Dash（連接號）/Hyphen（連字號）8-3.3、July 1-December 31、ages 65-75Taipei-Tokyo flightword-of-mouthX8中文文稿一律使用教育部《重訂標點符號手冊》中所訂之全形標點符號句號「。」、逗號「，」、頓號「、」、分號「；」、冒號「：」、問號「？」、驚嘆號「！」、單引號「」、雙引號『』、括號（）、破折號「──」、刪節號「……」、音界號「‧」、書名號「《》」、篇名號「〈〉」。破折號與刪節號一律佔兩格全形字元，其餘標點符號均佔一格；書名與篇名連用時，可省略篇名號。X9引號用於標示說話、引語、特別指稱或強調的詞語。先單引號，再雙引號。老師說：「你們要記住國父說的『青年要立志做大事，不要做大官』這句話。」X10中文用到括號（）時，用於行文中需要注釋或補充說明，前後符號各占一個字的位置，居正中。前半不出現在一行之末，後半不出現在一行之首。蘇軾，字子瞻，號東坡居士，宋眉山（今四 川省 眉山縣）人。X11英文單雙引號 '', "" 的用法美式英文：Angela had the nerve to tell me “When I saw ‘BYOB’ on your invitation, I assumed it meant ‘Bring Your Old Boyfriend.’”英式英文： ' "a" '，剛好跟美式英文相反X採用美式英文？AI 翻譯工具說明一、使用方式在英文、簡體中文的儲存格中輸入： TranslateCell("要翻譯的繁體中文儲存格", "目標語言", "屬性")參數1: 請指定你要翻譯內容的所在欄位（繁體中文）目標語言：英文( "en" ), 簡體中文 ( "zh-CN" )屬性：“標題”, "按鈕" ; 若為一般內文，則可以直接留白使用範例：函式（英文）：“=TranslateCell($C5,"en",$A5)”函式（簡體中文）：“=TranslateCell($C5,"zh-CN",$A5)”將函式翻譯後的儲存格複製，並僅貼上值，只貼上純文字的內容方便編修，未來翻譯內容也才不會一直動態改變。取得純文字後，再進行人工審核與調整。二、使用注意事項請留意中英文內容是否缺少標點符號，例如：沒有句號固定句型請更新至 FixedPhrases，慣用字請記得更新到Glossary，包含像是地形名稱等，未來可能會再次用到的翻譯，就記得更新固定句型的檢查要留意標點符號正確及完整，不然可能會比對失敗，而由AI 重新做翻譯。例如，以下缺乏句號的文案，就會比對失敗：『將\_\_\_\_升級為\_\_\_\_，土地血量高，無法放置怪獸。』『將\_\_\_\_升級為\_\_\_\_，土地血量高，無法放置怪獸』有時候太大量翻譯還是會失敗，如果確認繁體中文無誤，可以刪掉該儲存格，重新貼上一次公式。內容比較長、包含諧音梗或是專有名詞，AI 翻譯上比較困難，再請記得多檢查一次。目前屬性有標記成『標題』、『按鈕』，會做格式檢查，若是一般句子就不需要特別標記。三、翻譯規則與 AI 處理邏輯說明標點符號英文：逗號、句號需緊接在前方字詞後，後方加一個空格，不可留空格在前。中文：使用全形標點，刪除多餘的半形符號。中英文混合：自動在中文與英文之間補一格空白。冒號（:）、驚嘆號（!）、句號（.）在英文中統一使用半形。​

1. **中英文結構**

* 中文標點換成英文標點時會做正確轉換，不會消失或多加。
* 英文標題使用標題式大小寫 (Title Case)，且依規則省略結尾句號。

​

1. **屬性判斷**

* 標題：翻譯時採 Title Case，不加句號。
* 按鈕：保持簡潔，用 Title Case，不加標點，動詞保持原型。
* 項目/用法：簡短明確，避免冗長。
* 道具名稱 (item)：需符合 Glossary，長度不可超過 26 半形字元，專有名詞首字母大寫。
* 無屬性標註的，則視為一般文字段落，正常翻譯並保留句尾句號。

​

1. **固定句型與 Glossary**

* 有固定句型時，會先比對並套用模板，避免留下「\_\_\_\_」。
* Glossary（詞彙表）先行替換，確保專有名詞一致，如「草原 → Meadow」「早餐車 → Breakfast Cart」。

​

1. **繁簡轉換**

* 繁體 → 英文：透過 Gemini 翻譯。
* 繁體 → 簡體：透過轉換函式直接處理，不依賴 AI，避免遺漏或字數截斷。

​

1. **長度與一致性**

* 翻譯時自動檢查字數限制（道具名稱 ≤ 26 半形字元）。

​​

***

### 參考資源： <a href="#can-kao-zi-yuan" id="can-kao-zi-yuan"></a>

1. 設計概念：
   1. ​[多語系 產品在設計時該考慮什麼，才能有好的使用者體驗？｜設計大舌頭 (designtongue.me)](https://designtongue.me/ux-design-for-internationalization/)
2. 中文規範來源：
   1. ​[清華大學論文寫作要點](http://thup.site.nthu.edu.tw/p/412-1210-9517.php?Lang=zh-tw)
   2. ​[教育部國語推行委員會編著，《重訂標點符號手冊》修訂版](https://language.moe.gov.tw/001/upload/files/site_content/m0001/hau/c2.htm)
3. 工具：
   1. 前端檢查工具：[https://github.com/huacnlee/autocorrect](https://github.com/huacnlee/autocorrect)
   2. 感覺好用的音節斷字：[Hyphnes- CSS: CAscading Style sheets](https://developer.mozilla.org/en-US/docs/Web/CSS/hyphens#suggesting_line_break_opportunities)
4. 英文規範來源：
   1. 專業翻譯社針對英文寫作的
      1. ​[WORDVICE](https://blog.wordvice.com.tw/%E5%AD%B8%E8%A1%93%E8%AB%96%E6%96%87%E5%AF%AB%E4%BD%9C%E4%B8%AD%E5%B8%B8%E8%A6%8B%E7%9A%84%E9%8C%AF%E8%AA%A4%EF%BC%9A%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F/)
      2. ​[華樂絲學術英文編修](https://www.editing.tw/blog/%E4%BB%8B%E7%B4%B9%E8%8B%B1%E6%96%87%E6%A8%99%E9%BB%9E%E7%AC%A6%E8%99%9F%E5%8F%8A%E6%AD%A3%E7%A2%BA%E7%94%A8%E6%B3%95.html)

​​
