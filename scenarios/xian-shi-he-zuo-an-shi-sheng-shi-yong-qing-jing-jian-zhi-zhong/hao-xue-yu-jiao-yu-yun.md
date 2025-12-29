# 澔學與教育雲

## 澔學與教育雲登入簡介

1. 澔學使用者（[澔學是什麼？](../../introductions/ming-ci-jie-shi/pagamo-zhu-ye/hao-xue.md#hao-xue-shi-shen-me)）通常都是透過親師生平台登入 PaGamO，在使用者第一次登入時會先確認使用者是否有授權 PaGamO 存取澔學資料，有才會轉跳 PaGamO 平台，我們同時能處理的登入人數為 100 人，超過就會進入等排隊登入中。
2. 使用者登入 PaGamO 是透過教育雲端帳號提供的登入服務，使用者可直接輸入教育雲端帳號，或使用縣市帳號登入。

<figure><img src="../../.gitbook/assets/image (24).png" alt="" width="375"><figcaption></figcaption></figure>

## 使用者登入後的系統流程

1. 使用者進入 PaGamO，我們根據澔學與教育雲的 API 資料更新使用者 user 的資料，如果過程更新失敗的話，使用者也可至個人設定頁面點擊手動驗證，來手動觸發完成資料更新。
2. 使用者如果使用澔學登入（排除花蓮縣），就會依據年段加入公開世界，並根據使用者資料給予教師權限，以及建立、加入或退出班級（通常是新北市或金門縣的學生）。
3. 如果使用者來自「縣市合作案」的合作縣市，就會觸發縣市合作案的專屬機制
   1. 如使用者的資料來自澔學，可以到[管理後台-澔學相關設](https://www.pagamo.org/admin/city_gov_case_ischool)定，教育雲則看「[教育雲相關設定](https://www.pagamo.org/admin/city_gov_case)」
   2. 當縣市的「啟用狀態」屬於開啟狀態時，屬於該縣市的師生就會觸發縣市合作案的相關機制



## 縣市合作案專屬機制（澔學與教育雲基本共用）

1. 縣市中的相關機制主要分有機制觸發條件、加入世界與班級、教材授權與移除、班級退出與封存，以及其他特殊設定等內容，以下將依序說明。

<figure><img src="../../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

### 機制觸發條件

1. 使用者每次登入，我們都會抓取使用者的最新資料，如想確認使用者資料可至[縣市合作案用戶授權查詢](https://www.pagamo.org/admin/city_gov_case/user_authorization_info)後台，輸入 UID 查詢使用者的最新登入時間與帶入的資料內容
2.  當使用者資料來自合作縣市，且該使用在「[台灣當前學年學期](https://www.pagamo.org/admin/academic_year)」中「當前學期」中也是屬於學生或老師身份時，才會觸專屬縣市的流程

    <figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### 加入世界與班級

1.  加入世界的相關條件：

    1. 依據「合約到期日」的設定，在此日期前使用者都可正常使用此世界
    2. 公校師生預設可以加入，私校則看「開放私校加入」是否開啟
    3.  教師身份只要符合學校條件就可加入世界，學生身份則要再看「可進入此世界的學生年級」

        <figure><img src="../../.gitbook/assets/image (25).png" alt="" width="375"><figcaption></figcaption></figure>


    4. 如果不開放所有私校加入，但有需要僅開放某間私校加入，則可以使用特殊學校清單（[範例](https://boniotw-my.sharepoint.com/:x:/r/personal/bonio_share_bonio_com_tw/_layouts/15/Doc.aspx?sourcedoc=%7BAA04B8A4-8004-4611-8618-DC47D2CD6574%7D\&file=%E7%AF%84%E4%BE%8B_OO%E7%B8%A3%E5%B8%82_%E7%89%B9%E6%AE%8A%E5%AD%B8%E6%A0%A1%E6%B8%85%E5%96%AE.xlsx\&action=default\&mobileredirect=true\&DefaultItemOpen=1)），需注意學生也會受到「可進入此世界的學生年級」限制，舉例：「可進入此世界的學生年級」僅開放  1-9 年級時，10-12 年級的學生即使屬於特殊學校，也會無法進入世界。

    <figure><img src="../../.gitbook/assets/image (26).png" alt="" width="375"><figcaption></figcaption></figure>
2.  加入班級的機制：

    1. 師生身上分別會帶有許多班級資訊，如系統發現使用者身上，帶有符合「[台灣當前學年學期](https://www.pagamo.org/admin/academic_year)」中「當前學期」的班級資料，就會先檢查系統是否有此班級，如有就會協助使用者加入班級，如無系統就會協助創建班級，再將使用者加入班級中
       1. 創建的班級名稱規則：學年-學期\_學校名稱\_班級名稱，舉例：113-1\_新泰國小\_601
    2. 校管職稱：如果使用者屬於老師身份，且身上具備後台設定的「特殊職稱」則會加入該校所有已存在的班級（注意因為這些校管老師身上的資料通常不會有所有班級，所以都要等其他師生登入創建班級後，該校管老師才會加入學校的所有班級）

    <figure><img src="../../.gitbook/assets/image (27).png" alt="" width="375"><figcaption></figcaption></figure>



    1. 校管帳號清單([範例](https://boniotw-my.sharepoint.com/:x:/r/personal/bonio_share_bonio_com_tw/_layouts/15/Doc.aspx?sourcedoc=%7B8109B0EB-C9C9-4C3B-9743-FBD0F30769CC%7D\&file=%E7%AF%84%E4%BE%8B_OO%E7%B8%A3%E5%B8%82_%E6%A0%A1%E7%AE%A1%E5%B8%B3%E8%99%9F%E6%B8%85%E5%96%AE_v2.xlsx\&action=default\&mobileredirect=true))：如果老師帶入的資料不具備校管職稱，或缺少特定班級資料時，可以透過校管帳號清單將老師加入全校的班級，或者是指定學校的指定班級中

<figure><img src="../../.gitbook/assets/image (70).png" alt="" width="375"><figcaption></figcaption></figure>

### 教材授權與移除

#### 教材授權

縣市合作案的教材授權有「全年級教材授權」和「班級授權清單」兩種方式，如果兩個授權方式同時存在，且使用者均符合授權條件時，就會同時授權該商品教材。以下將說明兩種的設定注意事項：

1.  全年級教材授權，設定時：

    1. 需要指定授權的學年學期（學年學期來源：台灣學年學期設定）
    2. 需要指定授權的年級（勾選，有 1-12 年即可選擇）
    3. 設定的教材商品需要具備「數位學習精進案自動授權」
    4. 公私校授權：指定授權是給公校、私校或者是公私校都授權



<figure><img src="../../.gitbook/assets/image (22).png" alt="" width="375"><figcaption></figcaption></figure>

1. 班級授權清單（[澔學範例](https://boniotw-my.sharepoint.com/:x:/r/personal/bonio_share_bonio_com_tw/_layouts/15/Doc.aspx?sourcedoc=%7B676B5EC6-0650-4A69-8D00-420D7F3DC597%7D\&file=%E6%BE%94%E5%AD%B8_%E7%8F%AD%E7%B4%9A%E6%8E%88%E6%AC%8A%E6%B8%85%E5%96%AE%E7%AF%84%E4%BE%8B_v1.xlsx\&action=default\&mobileredirect=true)、[教育雲範例](https://boniotw-my.sharepoint.com/:x:/r/personal/bonio_share_bonio_com_tw/_layouts/15/Doc.aspx?sourcedoc=%7B9F7F0564-1554-403B-AD90-1A3B3B8ED84A%7D\&file=113-1_XX%E7%B8%A3%E5%B8%82_OO%E5%9C%8B%E4%B8%AD%E5%B0%8F_%E7%8F%AD%E7%B4%9A%E6%8E%88%E6%AC%8A%E6%B8%85%E5%96%AE%EF%BC%88%E5%9B%BA%E5%AE%9A%E6%95%99%E6%9D%90%EF%BC%89.xlsx\&action=default\&mobileredirect=true)）
   1. 注意班級授權清單中的教材名稱要跟「[商品列表](https://www.pagamo.org/admin/products/subscribe_products)」的商品名稱一致才會生效
   2. 商品必須具備「數位學習精進案自動授權」，才會觸發自動授權

<figure><img src="../../.gitbook/assets/image (23).png" alt="" width="375"><figcaption></figcaption></figure>

#### 教材移除：

1. 當後台移除教材授權後，要等使用者登入才會觸發教材的移除流程，移除後老師在教師後台也無法看到同學的任務答題數據。

### 班級退出與封存

教育雲：以身份區分，有校管權限/無校管權限（老師、學生）

#### 老師和學生自動封存與退出班級

1. 檢查API學年學期與當前學年學期是否一致
   * 若不一致，則不動作
   * 若一致，則繼續判斷2.
2. 檢查已加入的PaGamO班級有在API資料中
   * 若有，則不動作
   * 若無，則繼續判斷3.
3. 檢查PaGamO班級學年學期 >= API 班級最大學年學期?
   * 若>= API最大學年學期，則會退出班級
   * 若\<API最大學年學期，則會判斷4.
4. 檢查用戶身份是否為教師？
   * 若非教師（就會是學生），封存該生的\<API學年學期的PaGamO班級
   * 若是教師，會在判斷5.
5. 檢查PaGamO班級學校代碼與API學校代碼是否一致？
   * 若一致，則代表老師還在同一所學校，就封存該位老師身上\<API學年學期的PaGamO班級
   * 若不一致，則代表老師已調校，即退出該位老師身上與API學校代碼不一致的PaGamO班級

#### 校管自動封存與退出班級

1. 校管帳號檢查「現有PaGamO班級學校代碼」與「API學校代碼」或是「校管帳號清單中的學校代碼」是否一致
   * 若不一致，則退出班級
   * 若一致，則繼續判斷2.
2. 判斷該帳號的API學年學期(edu-info)與當前學年學期是否一致
   * 若不一致，則不動作
   * 若一致，則繼續判斷3.
3. 判斷已加入的 PaGamO 班級學年學期是否 < 當前學年學期?
   * 若是 < 當前學年學期，封存已加入的PaGamO班級
   * 若 = 當前學年學期，不動作
   * 若 > 當前學年學期，則退出已加入的 PaGamO 班級<br>



<details>

<summary>校管權限封退班級補充說明</summary>

* 調校的校管會直接退出班級，由其他還留在原校的老師或校管觸發封存班級
* 校管權限封存機制也須判斷當前學年學期，運營較好向老師宣達封存班級的時間
* 如果是校管帳號，就不會在處理學生或老師流程時，觸發退出與封存邏輯。會等到處理校管加入班級後才處理退出封存班級

</details>





### 縣市合作案重要文件

1. [澔學串接機制](https://www.figma.com/board/q93nPzlkCkL1u37WI8xCsd/%E6%BE%94%E5%AD%B8%E4%B8%B2%E6%8E%A5%E6%A9%9F%E5%88%B6%E8%A6%8F%E5%8A%83%EF%BC%88112-1%E9%96%8B%E5%A7%8B%EF%BC%89?node-id=0-1\&node-type=canvas\&t=IHc85ZXD02ItNhsv-0)：線上版都會在最上方
2. [教育雲串接機制](https://www.figma.com/file/43zueGdZWB4MMHGDT0yjsg/%E6%95%99%E8%82%B2%E9%9B%B2%E4%B8%B2%E6%8E%A5%E6%A9%9F%E5%88%B6\(112-1%E9%96%8B%E5%A7%8B\)?type=whiteboard\&node-id=0-1)：線上版都會在最上方
3. redmine：[113-1](https://redmine.bonio.com.tw/issues/38265)，可以從 Related issues 看到不同學期的票









