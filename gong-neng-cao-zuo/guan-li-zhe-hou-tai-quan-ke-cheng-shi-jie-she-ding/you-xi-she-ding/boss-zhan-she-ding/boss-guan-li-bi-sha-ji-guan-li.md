# BOSS 管理 / 必殺技管理

### 如何**新增必殺技？**

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> 必殺技管理</mark>

<figure><img src="../../../../.gitbook/assets/截圖 2023-06-29 15.55.20.png" alt="" width="563"><figcaption></figcaption></figure>

請依照需求填寫該必殺技的各項數值

* 必殺技名稱：​英中名稱 / 繁中名稱 / 簡中名稱​
* 損血：必殺技所​造成的傷害量
* 回血：必殺技所回復的血量​
* 減傷：​減少玩家對於 BOSS 的傷害長達數秒​，分別填入減傷比例；持續秒數
* 施毒：​每過一段時間所造成的傷害量，各別填入每圈所造成的傷害；每圈秒數；總圈數（會顯示在人物頭像周圍）​
* 說明：​英文說明 / 繁中說明 / 簡中說明​

{% hint style="info" %}
以上技能可以累加，例如蔓生怪的噬血纏繞就是損血＋回血
{% endhint %}

{% hint style="danger" %}
如有新的效果需要開發（損血、回血、減傷、施毒以外的效果），請先告知 PM
{% endhint %}

### 如何新增任務魔王？

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<figure><img src="../../../../.gitbook/assets/截圖 2023-06-29 15.28.13.png" alt="" width="563"><figcaption><p>貼心提醒：如果不確定BOSS的各設定項目該怎麼填寫，可以參考其他已存在的 BOSS 的設定項目</p></figcaption></figure>

請依照以下內容填寫 BOSS 的各個設定項目

<table><thead><tr><th width="225">設定項目</th><th>填入內容</th></tr></thead><tbody><tr><td>BOSS 名稱</td><td>請輸入英中 / 繁中 / 簡中名稱</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-1">類型</a></td><td>請選擇任務魔王 "Mission"</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-2">難度</a></td><td>請在 Easy / Normal / Hard 中選擇難度<br>※ 不同難度在教師後台代表不同隻魔王</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-3">血量</a></td><td>此處設為固定值１即可<br>※ 血量的多寡會依照教師介面的任務魔王設定人數計算</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-4">怒氣值上限</a></td><td>此處設為 1 即可</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-5">怒氣值與傷害比例</a></td><td>此處設為 1 即可</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-6">積分比值</a></td><td>請填入造成傷害量與積分的佔比<br>※ 最大為 1 不可超過</td></tr><tr><td>開放日、開放與結束時間</td><td>選擇魔王戰出現的星期別、開始結束時間</td></tr><tr><td>人數上限</td><td><p>請填入該次任務魔王戰役的人數上限</p><p>※ 進場人數達該數字後無法入場，需等待有人血量歸零後才能中途加入</p></td></tr><tr><td>必殺技</td><td>請選擇該魔王對應的必殺技<br>※ 可參閱<a href="../../../you-xi-jie-mian/mo-wu-zhi-zhen-cao-zuo.md#mo-wang-yu-qi-dui-ying-de-bi-sha-ji-wei-he">本表</a></td></tr><tr><td>怪獸圖</td><td>請分別上傳魔王懸賞 / 魔王本人 / 被捕捉 / 大頭圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>背景圖</td><td>請上傳背景圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>必殺技頭像</td><td>非必要上傳項目，可上傳 Web / Mobile 橫幅圖</td></tr><tr><td>說明</td><td>請輸入英中 / 繁中 / 簡中說明</td></tr></tbody></table>

{% hint style="danger" %}
請勿編輯現有的 BOSS，會造成不可預期的錯誤
{% endhint %}

### 如何新增官方魔王？

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<figure><img src="../../../../.gitbook/assets/截圖 2023-06-29 15.28.13.png" alt="" width="563"><figcaption><p>貼心提醒：如果不確定BOSS的各設定項目該怎麼填寫，可以參考其他已存在的 BOSS 的設定項目</p></figcaption></figure>

請依照以下內容填寫 BOSS 的各個設定項目

<table><thead><tr><th width="225">設定項目</th><th>填入內容</th></tr></thead><tbody><tr><td>BOSS 名稱</td><td>請輸入英中 / 繁中 / 簡中名稱</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-1">類型</a></td><td>請選擇官方魔王 "Official"</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-2">難度</a></td><td>此處設為 "Normal" 即可<br>※ 本質無意義</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-3">血量</a></td><td>請填入血量值<br>※ 一個玩家平均一分鐘可以打出 135 的傷害值，可以考慮人數上限與該值，並設想希望玩家在多少時間內打敗該魔王（血量 = 135 * 人數 * 時間）</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-4">怒氣值上限</a></td><td>此處設為 10000 即可</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-5">怒氣值與傷害比例</a></td><td><p>請填入造成怒氣值與傷害量的比例值</p><p>※ 比值越高，必殺技施展的頻率越高</p></td></tr><tr><td><a data-footnote-ref href="#user-content-fn-6">積分比值</a></td><td>請填入造成傷害量與積分的比例值<br>※ 最大為 1 不可超過；比值越高，所獲得的積分越高</td></tr><tr><td>開放日、開放與結束時間</td><td>選擇魔王戰出現的星期別、開始結束時間</td></tr><tr><td>人數上限</td><td><p>請填入該次官方魔王戰役的人數上限</p><p>※ 進場人數達該數字後無法入場，需等待有人血量歸零後才能中途加入</p></td></tr><tr><td>必殺技</td><td>請選擇該魔王對應的必殺技<br>※ 可參閱<a href="../../../you-xi-jie-mian/mo-wu-zhi-zhen-cao-zuo.md#mo-wang-yu-qi-dui-ying-de-bi-sha-ji-wei-he">本表</a></td></tr><tr><td>怪獸圖</td><td>請分別上傳魔王懸賞 / 魔王本人 / 被捕捉 / 大頭圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>背景圖</td><td>請上傳背景圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>必殺技頭像</td><td>非必要上傳項目，可上傳 Web / Mobile 橫幅圖</td></tr><tr><td>說明</td><td>請輸入英中 / 繁中 / 簡中說明</td></tr></tbody></table>

{% hint style="danger" %}
請勿編輯現有的 BOSS，會造成不可預期的錯誤
{% endhint %}

### 如何新增強襲魔王？

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<figure><img src="../../../../.gitbook/assets/截圖 2023-06-29 15.28.13.png" alt="" width="563"><figcaption><p>貼心提醒：如果不確定BOSS的各設定項目該怎麼填寫，可以參考其他已存在的 BOSS 的設定項目</p></figcaption></figure>

請依照以下內容填寫 BOSS 的各個設定項目

<table><thead><tr><th width="225">設定項目</th><th>填入內容</th></tr></thead><tbody><tr><td>BOSS 名稱</td><td>請輸入英中 / 繁中 / 簡中名稱</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-1">類型</a></td><td>請選擇強襲魔王 "Raid"</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-2">難度</a></td><td>此處設為 "Normal" 即可<br>※ 本質無意義</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-3">血量</a></td><td>請填入血量值<br>※ 一個玩家平均一分鐘可以打出 135 的傷害值，可以考慮人數上限與該值，並設想希望玩家在多少時間內打敗該魔王（血量 = 135 * 人數 * 時間）</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-4">怒氣值上限</a></td><td>此處設為 10000 即可</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-5">怒氣值與傷害比例</a></td><td><p>請填入造成怒氣值與傷害量的比例值</p><p>※ 比值越高，必殺技施展的頻率越高</p></td></tr><tr><td><a data-footnote-ref href="#user-content-fn-6">積分比值</a></td><td>請填入造成傷害量與積分的比例值<br>※ 最大為 1 不可超過；比值越高，所獲得的積分越高</td></tr><tr><td>開放日、開放與結束時間</td><td>選擇魔王戰出現的星期別、開始結束時間</td></tr><tr><td>人數上限</td><td><p>請填入該次強襲魔王戰役的人數上限</p><p>※ 進場人數達該數字後無法入場，需等待有人血量歸零後才能中途加入</p></td></tr><tr><td>必殺技</td><td>請選擇該魔王對應的必殺技<br>※ 可參閱<a href="../../../you-xi-jie-mian/mo-wu-zhi-zhen-cao-zuo.md#mo-wang-yu-qi-dui-ying-de-bi-sha-ji-wei-he">本表</a></td></tr><tr><td>怪獸圖</td><td>請分別上傳魔王懸賞 / 魔王本人 / 被捕捉 / 大頭圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>背景圖</td><td>請上傳背景圖<br>※ 可參閱<a href="https://boniotw-my.sharepoint.com/:f:/g/personal/bonio_share_bonio_com_tw/EiSpRgLo7TZBv1fDpNe19TUBKLUjDxSz8VrS_1A8JBMaJg?e=9Bl8gh">本檔案</a></td></tr><tr><td>必殺技頭像</td><td>非必要上傳項目，可上傳 Web / Mobile 橫幅圖</td></tr><tr><td>說明</td><td>請輸入英中 / 繁中 / 簡中說明</td></tr></tbody></table>

{% hint style="danger" %}
請勿編輯現有的 BOSS，會造成不可預期的錯誤
{% endhint %}

### 如何將魔王加進世界？

<mark style="background-color:purple;">設定位置：管理者後台 -> 遊戲設定 -> BOSS 戰設定 -> BOSS 管理</mark>

<figure><img src="../../../../.gitbook/assets/截圖 2023-06-29 16.01.06.png" alt="" width="563"><figcaption></figcaption></figure>

點擊該 BOSS 「課程與錯題設定」列下的「編輯」，並輸入該世界的名稱，即可於底下的世界列表找到該世界，點擊後則會於右方出現打勾的符號，即代表該 BOSS 已應用至該課程世界，即完成設定。

如何開放玩家以一般任務作為官方魔王的答題拉元

* 開放玩家以一般任務作為世界魔王的答題來源
* 設定管理者可用的任務魔王
* 設定教師可用的任務魔王

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
