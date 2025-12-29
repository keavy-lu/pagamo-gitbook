# 設置任務魔王戰

### 如何設置任務魔王戰？

<details>

<summary>第一步：確認 BOSS 清單是否有使用者想要使用的 BOSS</summary>

<mark style="background-color:purple;">檢視位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-29 14.17.34 (1).png" alt="貼心提醒：可以先檢查 BOSS 的類型是不是想要使用的類型，再接著檢查其他設定項目" data-size="original">

逐一點擊魔王類型為 Mission 的最後一欄的欄位旁的「編輯」，查看「所有設定項目」，確認全部設定項目皆與自己想要設定的數值相同。

***

如對於魔王的設定項目仍有不清，可以參閱「[新增魔王](she-zhi-ren-wu-mo-wang-zhan.md#xin-zeng-ren-wu-mo-wang)」的 Tooltips

</details>

<details>

<summary>第二步：確認欲使用的 BOSS 是否為新 BOSS</summary>

<mark style="background-color:purple;">檢視位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> 必殺技管理</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-29 15.52.19.png" alt="貼心提醒：可以查看必殺技的說明了解必殺技的效果" data-size="original">

需要確認必殺技列表中是否具備欲設定 BOSS 的必殺技。如列表中有該 BOSS 的必殺技，則其為舊 BOSS；如列表中無該 BOSS 的必殺技，則其為新 BOSS。

</details>

<details>

<summary>第三步：判斷設置 BOSS 情形</summary>

完成步驟一與步驟的二前置作業後，依據不同狀態可分為三種情形，請依照該情形對應的流程步驟進行設置。

**情形一：倘若 BOSS 清單已有想要使用的 BOSS**

1. [將魔王加進世界](she-zhi-ren-wu-mo-wang-zhan.md#jiang-mo-wang-jia-jin-shi-jie)
2. [開啟任務魔王的其他必要設定](she-zhi-ren-wu-mo-wang-zhan.md#kai-qi-ren-wu-mo-wang-de-qi-ta-bi-yao-she-ding)

**情形二：倘若 BOSS 清單沒有想要使用的 BOSS，且該此 BOSS 為新 BOSS**

1. [新增必殺技](she-zhi-ren-wu-mo-wang-zhan.md#xin-zeng-bi-sha-ji)
2. [新增任務 BOSS](she-zhi-ren-wu-mo-wang-zhan.md#xin-zeng-ren-wu-mo-wang)
3. [將魔王加進世界](she-zhi-ren-wu-mo-wang-zhan.md#jiang-mo-wang-jia-jin-shi-jie)
4. [開啟任務魔王的其他必要設定](she-zhi-ren-wu-mo-wang-zhan.md#kai-qi-ren-wu-mo-wang-de-qi-ta-bi-yao-she-ding)

**情形三：倘若 BOSS 清單沒有想要使用的 BOSS，且該此 BOSS 為舊 BOSS**

1. [新增任務 BOSS](she-zhi-ren-wu-mo-wang-zhan.md#xin-zeng-ren-wu-mo-wang)
2. [將魔王加進世界](she-zhi-ren-wu-mo-wang-zhan.md#jiang-mo-wang-jia-jin-shi-jie)
3. [開啟任務魔王的其他必要設定](she-zhi-ren-wu-mo-wang-zhan.md#kai-qi-ren-wu-mo-wang-de-qi-ta-bi-yao-she-ding)

</details>

<details>

<summary>新增必殺技</summary>

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> 必殺技管理</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-29 15.55.20.png" alt="" data-size="original">

請依照需求填寫該必殺技的各項數值

* 必殺技名稱：​英中名稱 / 繁中名稱 / 簡中名稱​
* 損血：必殺技所​造成的傷害量
* 回血：必殺技所回復的血量​
* 減傷：​減少玩家對於 BOSS 的傷害長達數秒​，分別填入減傷比例；持續秒數
* 施毒：​每過一段時間所造成的傷害量，各別填入每圈所造成的傷害；每圈秒數；總圈數（會顯示在人物頭像周圍）​
* 說明：​英文說明 / 繁中說明 / 簡中說明​

***

以上技能可以累加，例如蔓生怪的噬血纏繞就是損血＋回血

***

如有新的效果需要開發（損血、回血、減傷、施毒以外的效果），請先告知 PM

</details>

<details>

<summary>新增任務魔王</summary>

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-29 15.28.13.png" alt="貼心提醒：如果不確定BOSS的各設定項目該怎麼填寫，可以參考其他已存在的 BOSS 的設定項目" data-size="original">

請依照以下內容填寫 BOSS 的各個設定項目：

1. BOSS 名稱：請輸入英中 / 繁中 / 簡中名稱
2. 類型[^1]：請選擇任務魔王 "Mission"
3. 難度[^2]：請在 Easy / Normal / Hard 中選擇難度\
   ※ 不同難度在教師後台代表不同隻魔王
4. 血量[^3]：此處設為固定值１即可\
   ※ 血量的多寡會依照教師介面的任務魔王設定人數計算
5. 怒氣值上限[^4]：此處設為 1 即可
6. 怒氣值與傷害比例[^5]：此處設為 1 即可
7. 積分比值[^6]：請填入造成傷害量與積分的佔比\
   ※ 最大為 1 不可超過
8. 開放日、開放與結束時間：選擇可指派魔王任務的星期別、開始結束時間\
   ※ 實質上不影響開設任務魔王戰的時間
9.  人數上限：請填入該魔王開設的任務魔王戰役的人數上限

    ※ 實質上不影響教師於教師後台設置的人數上限\
    ※ 進場人數達該數字後無法入場，需等待有人血量歸零後才能中途加入
10. 必殺技：請選擇該魔王對應的必殺技\
    ※ 可參閱[本表](../../../introductions/you-xi-zhu-yao-gong-neng-jie-shao/mo-wu-zhi-zhen-jie-shao.md#mo-wang-yu-qi-dui-ying-de-bi-sha-ji-wei-he)
11. 怪獸圖：請分別上傳魔王懸賞 / 魔王本人 / 被捕捉 / 大頭圖\
    ※ 可參閱[本檔案](https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh)
12. 背景圖：請上傳背景圖\
    ※ 可參閱[本檔案](https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh)
13. 必殺技頭像：非必要上傳項目，可上傳 Web / Mobile 橫幅圖
14. 說明：請輸入英中 / 繁中 / 簡中說明

***

請勿編輯現有的 BOSS，會造成不可預期的錯誤

</details>

<details>

<summary>將魔王加進世界</summary>

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-29 16.01.06.png" alt="" data-size="original">

點擊該 BOSS 「課程與錯題設定」列下的「編輯」，並輸入該世界的名稱，即可於底下的世界列表找到該世界，點擊後則會於右方出現打勾的符號，即代表該 BOSS 已應用至該課程世界，即完成設定。

</details>

<details>

<summary>開啟任務魔王的其他必要設定</summary>

<mark style="background-color:purple;">設定位置：管理者後台 -> 欲設定的課程世界 -> 課程設定 -> 進階設定 -> 魔王戰</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-30 14.31.04.png" alt="貼心提醒：請記得滑到最下方並點及「編輯」再進行調動" data-size="original">

* 開啟「開放魔物指針」、「世界魔王答題可選擇一般任務」
* 於「管理者權限魔王任務」與「教師權限魔王任務」中點選類型為 Mission 且被納入該課程世界的魔王

</details>

<details>

<summary>設定任務魔王戰</summary>

<mark style="background-color:purple;">設定位置：教師後台 -> 作業管理 -> 作業清單 -> 新增任務</mark>

<img src="../../../.gitbook/assets/截圖 2023-06-30 14.50.25.png" alt="" data-size="original">

（請確保[<mark style="color:blue;">已創建作業</mark>](../../teacher_console/zuo-ye-guan-li/zuo-ye.md#ru-he-jian-li-zuo-ye)<mark style="color:blue;">）</mark>

1. 請先選擇「魔王模式」作為任務的模式
2. 填入任務名稱
3. 選擇任務的開始時間與結束時間（時間僅限於 1～20 分鐘）
4. 選擇答案顯示設定（此設定值無意義，皆不會顯示正確答案與詳解）
5. 點選「魔王設定」，並完成以下設定
   * 選擇魔王難度（不同難度的魔王在後台為不同隻魔王，若無法選擇其他難度，代表後台並無設定該難度的魔王）
   * 填入參加人數（參加人數設定越高，魔王血量越高）
6. 點擊「下一步」，將任務指派給班級或小組（屆時就會扣除 QP）
7. 開設魔王任務會耗費教師 2000 QP[^7]，用於給予學生參與魔王戰的獎勵
8. 不像是一般任務，學生答對任務內的題目並不會獲得任何 QP

</details>

[^1]: 共有三種可以選擇的項目\
    &#x20;\- Mission：任務魔王\
    &#x20;\- Official：官方魔王\
    &#x20;\- Raid：強襲魔王\
    不同模式需選擇不同魔王種類

[^2]: 魔王強度越強，魔王越難擊敗

[^3]: 魔王血量越高，魔王越難擊敗

[^4]: 本值並無實質

[^5]: 魔王被打後會累積的怒氣，怒氣滿就會發動必殺技一次，此處為比值，如填寫 0.5 ，則玩家對魔王造成 10000 的傷害，魔王的怒氣值會上升 5000

[^6]: 個人累積傷害力可以兌換的積分比值

[^7]: 題目點數，可以用來購買任務獎勵
