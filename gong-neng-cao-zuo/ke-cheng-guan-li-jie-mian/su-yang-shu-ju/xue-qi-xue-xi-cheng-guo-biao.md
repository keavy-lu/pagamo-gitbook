# 學期學習成果表

{% hint style="warning" %}
如果無法於課程管理界面中看到此素養數據功能，原因可能為二：

1. 目前並無持有課程擁有者的權限，詳情參考[此連結](../../guan-li-zhe-hou-tai-ke-cheng-shi-jie-she-ding/you-xi-jue-se-guan-li.md#ru-he-da-kai-you-hu-jiao-se-de-quan-xian)
2. 並未於管理者後台的進階設定中設定課程管理介面開關，詳情參考[此連結](../../guan-li-zhe-hou-tai-ke-cheng-shi-jie-she-ding/jin-jie-she-ding/ke-cheng-guan-li-jie-mian-kai-guan.md#ru-he-da-kai-ke-cheng-guan-li-jie-mian-de-su-yang-shu-ju-gong-neng)
{% endhint %}

### 如何在課程管理介面中下載學期學習成果表？

<mark style="background-color:purple;">設定位置：課程管理介面 -> 素養數據 -> 學期學習成果表</mark>

<figure><img src="../../../.gitbook/assets/截圖 2023-08-14 12.11.12.png" alt="" width="563"><figcaption></figcaption></figure>

課程管理者能夠選定師生帳號管理介面的年級與班級、上下學期劃分的日期、素養教材類別，作為學期學習成果表的數據篩選依據，詳細步驟如下：

1. 設定課程（如非目前所在的課程世界，請切換成欲下載資訊的課程世界）
2. 設定要下載的年級與班級（此年級與班級的設定值是取自於帳號管理介面，教師自建班級不在此列）
3. 選擇素養教材
4. 選擇素養商品
5. 選擇上學期或下學期的任務派發起始日～結束日
6. 設定學期成果表的輸出方式
   * 每個學生一份：每個學生都會輸出一份 PDF，此 PDF 僅包含該學生個人的學期成果表
   * 一個班級一份：一個班級只會輸出一份 PDF，此 PDF 中包全班學生的學期成果表
   * 包含兩種輸出方式（同時有班級與學生的分類架構）：系統會依據「班級」建立資料夾，並把屬於該班級學生的學期成果表 PDF 輸出至此班級資料夾下
7. 設定是否顯示平均數值
   * 班級平均
   * 年級平均
   * 全國平均
8. 決定是否顯示測驗任務
9. 點擊「產生學期成果表」下載學期學習成果表

{% hint style="info" %}
1) 平均正確率算法 = （學生有完成任務之正確率加總）/ （所有完成任務數）
2) 平均完成率算法 = （加總所有學生完成的任務數 / 加總所有學生有收到的的任務數）
{% endhint %}

{% hint style="info" %}
何時系統會收到任務的成績（user\_missions）？

* 一般任務：按下完成任務按鈕
* 測驗任務：完成測驗（並非完成任務按鈕，因為很多學生都會忘記點擊「完成任務」）
{% endhint %}
