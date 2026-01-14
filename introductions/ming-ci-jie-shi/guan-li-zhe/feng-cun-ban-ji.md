# 封存班級

### 封存班級是什麼？

封存班級為一種班級的狀態，為使用中班級與隱藏班級以外的第三種狀態。封存班級能夠保留用戶的使用軌跡：包含老師在平台管理過的班級、建過的作業、派過的任務以及所帶班級學生學習數據；學生在平台收到的任務、訊息，各種與老師、同學間的互動紀錄。不像是隱藏班級，老師仍能夠查看封存狀態的班級與學生資訊。

在各個介面中，不同狀態的班級的操作區別為：

#### **教師後台：我的班級、遊戲入口管理、訊息管理、素養數據、作業管理、統計分析**

<table><thead><tr><th width="273">操作</th><th width="130">正常自建班級</th><th width="150">正常非自建班級</th><th width="97">封存班級</th><th>隱藏班級</th></tr></thead><tbody><tr><td>查看班級</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>編輯班級</td><td>O</td><td>X</td><td>X</td><td>X</td></tr><tr><td>刪除班級</td><td>O</td><td>X</td><td>X</td><td>X</td></tr><tr><td>新增學生<br>（匯入/提供班級代碼）</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td>查看學生</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>編輯學生<br>（暱稱、座號、分組）</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td>移除學生</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td>遊戲入口管理<br>（關閉或開啟）</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-1">X</a></td><td>O</td></tr><tr><td>新增訊息</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td>查看訊息</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>編輯訊息</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>刪除訊息</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>查看素養數據</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-2">O</a></td><td>X</td></tr><tr><td>下載素養數據</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-3">O</a></td><td>X</td></tr><tr><td>派發任務</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td>查看任務</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>編輯任務設定與題目來源</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>刪除任務</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>查看任務數據</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-4">O</a></td><td>X</td></tr><tr><td>下載數據</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-3">O</a></td><td>X</td></tr></tbody></table>

{% hint style="info" %}
在使用統計分析功能時，因為其撈取邏輯是撈取作業而非任務，所以可查看、下載的邏輯為

1. 若作業可對應多個任務 -> 只要有其中一個任務開始時間小於封存時間，就顯示該作業
2. ﻿﻿若作業無法對應到任務 -> 顯示該作業，例如：競賽之盾
{% endhint %}

#### **帳號管理後台：班級管理**

<table><thead><tr><th width="273">操作</th><th width="130">正常自建班級</th><th width="150">正常非自建班級</th><th width="97">封存班級</th><th>隱藏班級</th></tr></thead><tbody><tr><td>新增班級</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-5">X</a></td><td>X</td></tr><tr><td>查看班級</td><td>O</td><td>O</td><td>O</td><td>X</td></tr><tr><td>編輯班級</td><td>O</td><td>X</td><td><a data-footnote-ref href="#user-content-fn-6">O</a> / <a data-footnote-ref href="#user-content-fn-7">X</a></td><td>X</td></tr><tr><td>刪除班級</td><td>O</td><td>O</td><td>O</td><td>X</td></tr></tbody></table>

#### **遊戲介面**

<table><thead><tr><th width="273">操作</th><th width="130">正常自建班級</th><th width="150">正常非自建班級</th><th width="97">封存班級</th></tr></thead><tbody><tr><td>查看班級</td><td>O</td><td>O</td><td>O</td></tr><tr><td>加入班級</td><td>O</td><td>O</td><td>X</td></tr><tr><td>查看班級訊息、個人訊息</td><td>O</td><td>O</td><td>O</td></tr><tr><td>接取班級任務</td><td>O</td><td>O</td><td><a data-footnote-ref href="#user-content-fn-8">O</a></td></tr><tr><td>查看戰績排名</td><td>O</td><td>O</td><td>O</td></tr><tr><td>查看學習分析</td><td>O</td><td>O</td><td>O</td></tr><tr><td>查看學習數據</td><td>O</td><td>O</td><td>O</td></tr></tbody></table>

[^1]: 封存班級後一律開啟遊戲入口

[^2]: 只能看到封存班級前所派發的任務與學生的在這些任務上的作答數據

[^3]: 只能下載封存班級前所派發的任務與學生的在這些任務上的作答數據

[^4]: 只能查看封存班級前所派發的任務與學生的在這些任務上的作答數據

[^5]: 無法直接從後台封存班級

[^6]: 可編輯

    1. 班級名稱
    2. 重設師生帳號
    3. 學生座號與老師姓名

[^7]: 

    不可編輯

    1. 班級所屬年級
    2. 班級排序（因為會影響到教師後台的排序）

[^8]: 仍會繼續收到使用中班級的任務；不會收到封存班級的任務
