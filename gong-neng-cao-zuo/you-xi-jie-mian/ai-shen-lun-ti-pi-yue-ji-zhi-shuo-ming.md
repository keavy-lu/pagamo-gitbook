# AI 申論題批閱機制說明

AI 申論題批閱機制為搭配 K12 自產學習內容「中文素養｜思辨表達」推出之功能，旨在透過 **閱讀 → 思考 → 表達** 的流程，訓練學生建立觀點、表達想法。

{% hint style="danger" %}
目前 AI 申論題功能僅開放 PaGamO 內部夥伴使用，是否開放至各個世界仍待 K12 各主管決議。
{% endhint %}

### 如何啟用 AI 申論題批閱功能？

步驟一：<mark style="background-color:purple;">管理者後台 >  課程設定 > 進階設定 > 教師後台設定</mark> 開啟「申論題型 AI 批改」，並選擇欲開放該世界的教師使用的 AI 批改方式（模型）。

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

步驟二：在 <mark style="background-color:purple;">教師後台 > 新增作業</mark> 選擇申論題，即可在 <mark style="background-color:$info;">題目預覽 > 題目設定</mark> 看見開啟「申論題型支援 AI 批改功能」的開關，並選擇對應的 AI 批改模型。

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

步驟三（非必要，但推薦進行）： <mark style="background-color:purple;">教師後台 > 新增作業 > 任務設定</mark> 勾選「題目顯示學生上一次作答內容」

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
如未看到「題目顯示學生上一次作答內容」選項，請至「管理者後台 > 課程設定 > 進階設定 > 教師後台設定」開啟開關
{% endhint %}

### AI 申論題批閱功能運作方式

#### 一、作答

1. 學生作答字數需達模型設定的回答字數下限，「AI 批閱」的按鈕才會啟用，讓學生可以批改。
   1. 回答字數下限：通用型批改 0 字；思辨表達（初階） 20 字；思辨表達（中階）、思辨表達（高階）50 字
2. 學生可直接打字，也可使用裝置內建的輸入法進行語音輸入。
3. 原則上題目與答案皆已禁止學生複製貼上，在少數裝置上學生仍可貼上，但最多僅能貼上 10 個字。
4. 多數情況下，系統將自動暫存學生撰寫的答案，若學生使用同裝置、同帳號、同任務，且不曾登出，答案可記憶 4 小時。
5. 學生可交白卷（完全不作答），系統將一律判定為學生答錯。

#### 二、批改

1. 學生點選「批改」後，AI 約需 5–10 秒的時間產出回饋評分與建議，批改期間可切換檢查其他題目。
   1. 若學生批改通過，學生可在按下「送出」以前，反覆修改答案並重新批改，但是一旦按下「送出」，即無法再修改。
   2. 若學生批改後未通過，則必須反覆修改、重新批改到通過，才可以按下「送出」。
2. 同一道題目需間隔 20 秒才可再次執行 AI 批改。
3.  過程中，題號將亮起橘燈，提醒使用者有未完成的項目：

    1. 已作答該題，但是尚未批改
    2. 已批改該題，但是未通過批改，或是玩家未查看批改結果

    <div align="left"><figure><img src="../../.gitbook/assets/image (76).png" alt="" width="185"><figcaption></figcaption></figure></div>
4. 若批改到一半網頁中斷，學生需重新點選批改。
5. 若 AI 服務異常，系統會優先讓學生通過，並註記「AI 批改異常」。

#### 三、追蹤與批閱

1. 系統將記錄每次的批改歷程與 AI 批改結果，並支援使用者於以下管道查看
   1. 學生：遊戲介面的<mark style="background-color:purple;">頭像 > 學習中心 > 學習數據</mark>
   2. 教師：<mark style="background-color:purple;">教師後台 > 班級作答狀況 > 任務數據 > 申論題批閱</mark>
2. 教師可於 <mark style="background-color:purple;">教師後台 > 班級作答狀況 > 任務數據 > 申論題批閱</mark> 送出批閱（可直接送出 AI 為老師寫好的批閱內容，或老師自行撰寫）。教師送出批閱後，學生會立即在 <mark style="background-color:purple;">訊息管理 > 帳號訊息</mark> 收到通知。

***

### 限制與注意事項

* 申論題僅支援一般模式與測驗模式，不支援電競功能（例如：魔物指針、競賽之盾、奪寶信號）。
* 教師端僅能查看「學生的 AI 批改歷程與批改當下的回答」，不可直接修改學生作答內容。



