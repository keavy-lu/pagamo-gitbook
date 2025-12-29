# 當前地圖

### 如何編輯當前地圖的地形？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 編輯地圖區塊</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51.png" alt="" width="563"><figcaption></figcaption></figure>

可以從左上角的地形列中得知編輯地形時可用的地形種類，點選欲填入的地形種類後，即可於主畫面中點選欲變成該地形的土地，也可以長按並拖曳至欲變成該地形的土地，不必逐一點擊。若需要結束編輯，需再次點擊土地。

電競賽分為個人賽與團體賽。倘若這張地圖用於個人賽，需要「右鍵點擊地形」，輸入「順序」 e.g. 若該七塊土地為第四個玩家所擁有的土地，則需要填入 4；若為該七塊土地為第十個玩家所擁有的土地，則需要填入 10。倘若這張地圖用於團體賽，需要「右鍵點擊地形」，輸入「組別與順序」 e.g. 若該七塊土地為第一組的第一個玩家所擁有的土地，則需要填入 1,1；若為該七塊土地為第三組的第二個玩家所擁有的土地，則需要填入 3,2。

### 如何編輯當前地圖的地圖資訊？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 編輯地圖資訊</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51 2.png" alt="" width="563"><figcaption></figcaption></figure>

1. 點擊「編輯地圖資訊」
2. 編輯地圖的名稱、尺寸與描述（同步會顯示在競賽後台選擇地圖的區塊）

### 如何編輯當前地圖的特殊地形設定？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 特殊玩法設定</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51 3.png" alt="" width="563"><figcaption></figcaption></figure>

如需更動特殊地形積分

1. 開啟「自訂土地積分」的 toggle
2. 調動砲台、碉堡、城堡的積分
3. 如需將其他地形設定為特殊地形並設定積分，可點擊 toggle 旁的「增加 icon」

如需設定引爆戰玩法

1. 開啟「加入引爆戰玩法」的 toggle
2. 調動每次佔領引爆點後，炸毀非自己陣營的領土數量

### 如何直接複製當前地圖？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 複製</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51 4.png" alt="" width="563"><figcaption></figcaption></figure>

可點擊「複製」，系統會複製該地圖所有座標地形，以及組別、特殊地形設定，在相同環境內新增一個新地圖。複製完後，頁面會跳轉至新地圖，並打開編輯資料頁，預設地圖名稱為：原地圖名稱（1）。

{% hint style="info" %}
與匯出當前地圖、取得地圖碼的功能不同，使用地圖的複製功能時，其所複製出的地圖僅能在相同環境中使用 e.g. Develop, Pre-deploy 等；而使用地圖碼時，則可以跨環境地複製地圖 e.g. Develop 的地圖，我可以利用 Develop 的地圖碼進行匯入，在正式環境出複製出相同地圖
{% endhint %}

### 如何匯出當前地圖，打包成地圖碼？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 匯出地圖</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51 5.png" alt="" width="563"><figcaption></figcaption></figure>

可點擊「匯出地圖」，系統會複製該地圖所有座標地形，以及組別、特殊地形設定，並打包成一串地圖碼。複製該段字串後，可以跳轉至不同環境，並在該環境中使用「地圖碼匯入地圖」的功能，在不同環境下複製出相同地圖。

{% hint style="info" %}
與複製地圖的功能不同，使用匯出當前地圖、取得地圖碼的複製功能時，可以跨環境地複製地圖 e.g. Develop 的地圖，我可以利用 Develop 的地圖碼進行匯入，在正式環境出複製出相同地圖；而在使用地圖的複製功能時，其所複製出的地圖僅能在相同環境中使用 e.g. Develop, Pre-deploy 等
{% endhint %}

### 如何刪除地圖？

<mark style="background-color:purple;">設定位置：選定地圖 -> 欲設定的地圖 -> 刪除</mark>

<figure><img src="../../.gitbook/assets/截圖 2023-09-01 18.29.51 6.png" alt="" width="563"><figcaption></figcaption></figure>

點擊「刪除」並確認，即可成功刪除。
