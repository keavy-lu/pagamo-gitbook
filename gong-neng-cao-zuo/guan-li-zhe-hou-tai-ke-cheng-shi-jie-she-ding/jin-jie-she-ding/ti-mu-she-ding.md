# 題目設定

<figure><img src="../../../.gitbook/assets/截圖 2023-08-04 17.46.30.png" alt="" width="563"><figcaption></figcaption></figure>

### 如何開啟答題時玩家分享詳解的標籤頁？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

開啟「開啟分享詳解」的 Toggle。

{% hint style="info" %}
如關閉「玩家分享詳解」的功能，則玩家只能看到只能看到官方詳解的標籤，自己與其他玩家皆無法分享題目的詳解
{% endhint %}

### 如何讓玩家於答題後強制查看詳解？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

開啟「強制看詳解」的 Toggle。

### 如何打開師生帳號管理的「玩家年級」的功能，並設定題目對應年級的機制？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

開啟「題目對應年級」的 Toggle，並設定玩家使用自選章節回答低於自己年級的題目時的傷害力、金錢下降幅度。而玩家若在遊戲介面的自選章節中選擇低於自己年級的題目時，會出現提示語「非適合年級的題目」。

{% hint style="info" %}
1. 未設定對應年級的題目將不受影響
2. 答對題目時結算介面的傷害力與金錢數字旁出現\[ i ]閃動圖示，點擊觀看詳細說明可看到損失的數值
{% endhint %}

{% hint style="warning" %}
1. 公開世界如國小天地、國中世界等，因玩家不便更新年級，不能開啟此開關
2. 再開啟此功能前，請確認該世界所有玩家的年級有[正確設定](../../shi-sheng-zhang-hao-guan-li-jie-mian/wan-jia-nian-ji.md#ru-he-she-ding-wan-jia-de-nian-ji)，且已經開出[ OP 票](https://redmine.bonio.com.tw/issues/20897)，將題庫設定為對應年段
{% endhint %}

### 如何設定同一題目的最高作答限制次數？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

於「閱讀答題限制送出時間」欄位選擇次數。

{% hint style="info" %}
同一題作答答對次數超過設定次數後，下一次再答對時的傷害力和金錢會被扣除變成 0
{% endhint %}

{% hint style="warning" %}
若該課程在管理者後台 -> 系統設定 -> 課程管理中被設定為可重複作答，將鎖定為不限次數
{% endhint %}

### 如何設定閱讀題組內最高的錯題次數？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

於「閱讀題組防刷分錯題次數」欄位中輸入限制次數。

{% hint style="info" %}
輸入數字後，若戶於同一閱讀題組中答錯達設定次數，再答錯將無法輸出傷害力
{% endhint %}

### 如何設定遊戲介面中第一次回答閱讀題組時的送出答案時間限制？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

於「閱讀答題限制送出時間」欄位選擇時間。

{% hint style="info" %}
1. 設定時間後，在遊戲介面第一次作答閱讀題組時，必須等待設定的時間過後才能送出答案
2. 僅有遊戲介面會有此限制，學習中心不受此限制影響
{% endhint %}

### 如何開放玩家放棄作答？

<mark style="background-color:purple;">設定位置：管理者後台 -> 課程世界設定 -> 進階設定 -> 題目設定區塊</mark>

開啟「玩家可以放棄作答」的 Toggle

{% hint style="info" %}
1. 若開啟此功能，該課程世界的玩家答題介面有「Ｘ」可以點擊來放棄作答，且放棄作答不影響學期數據計算規則
2. 若有設置「閱讀答題限制送出時間」的欄位，請關閉「開放玩家放棄作答」的 Toggle
{% endhint %}
