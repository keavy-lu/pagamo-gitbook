---
description: 與機制
---

# 遊戲介面介紹與機制

### 答題一次的體力耗損與對應的攻擊或訓練數值為何？ <a href="#ban-ji-shi-shen-me" id="ban-ji-shi-shen-me"></a>

答題將消耗能量，而答對與答錯各別消耗的能量會有所不同：

<table><thead><tr><th width="235.33333333333331"></th><th>數值</th></tr></thead><tbody><tr><td>攻擊時答對</td><td>消耗 6 能量</td></tr><tr><td>攻擊時答錯或放棄作答</td><td>消耗 15 能量</td></tr><tr><td>訓練時答對</td><td>消耗 4 能量</td></tr><tr><td>訓練時答錯或放棄作答</td><td>消耗 10 能量</td></tr><tr><td>攻擊力</td><td>計算方式詳見<a href="you-xi-jie-mian-jie-shao-yu-ji-zhi.md#ban-ji-shi-shen-me-2">此部分</a></td></tr><tr><td>訓練血量</td><td>單次成功訓練，土地的血量會上升 60</td></tr><tr><td>經驗值</td><td>100（角色加成另計）</td></tr><tr><td>金錢（功勳）</td><td>100（角色加成另計）</td></tr><tr><td>攻擊時爆擊可能性</td><td>有</td></tr></tbody></table>

{% hint style="info" %}
如要查看[省力模式](../../introductions/ming-ci-jie-shi/wan-jia/sheng-li-mo-shi.md#sheng-li-mo-shi-shi-shen-me)下的體力耗損與攻擊數據，可參考[此連結](../../introductions/ming-ci-jie-shi/wan-jia/sheng-li-mo-shi.md#sheng-li-mo-shi-shi-shen-me)
{% endhint %}

### 攻擊力如何計算？ <a href="#ban-ji-shi-shen-me" id="ban-ji-shi-shen-me"></a>

攻擊力由以下內容所構成：基礎傷害、難度加成、時間加成、題目集加成、爆擊、角色加成、道具加成，而其計算方式為：

<mark style="background-color:blue;">攻擊力 = \[ 基本值 40 x (1 + 難度 + 答題速度 + 暴擊加成 ) + 題目集加成 ] x (角色能力) + 道具加成</mark>

<table><thead><tr><th width="137.33333333333331"></th><th>數值</th></tr></thead><tbody><tr><td>基本傷害</td><td>基本值＊1，因此固定為 40 </td></tr><tr><td>難度加成</td><td>基本值＊1 / [1 + e^(-x/(1-0.9x))]，x 為這題平均答對率</td></tr><tr><td>時間加成</td><td>基本值＊[1/(x+1)]^0.5, x為所花時間佔題目可作答時間比例</td></tr><tr><td>題目集加成</td><td>做題目集的話為 5，否則為 0</td></tr><tr><td>爆擊</td><td>基本值＊<a data-footnote-ref href="#user-content-fn-1">Round ( 等級 / 100, 2 )</a></td></tr><tr><td>角色加成</td><td>依據遊戲角色加成</td></tr><tr><td>道具加成</td><td>我方使用狂戰士飛斧：增加額外 8 ~ 12 傷害<br>敵方使用巨像手甲：減少 50% 傷害</td></tr></tbody></table>

{% hint style="info" %}
1. 暴擊**只有 20 級以上**才會發生，1\~19 級暴擊率為 0，20 級以上每次戰鬥有 10% 機率出現暴擊，當暴擊發生時，攻擊力會加上暴擊力
2. 使用迅擊者拳套可讓爆擊率加倍，變為 20％
{% endhint %}

{% hint style="info" %}
以上數據會受到後台管理者於課程設定的進階設定的影響，如玩家回答比自己年級數更低的題目，且後台管理者有設定[題目對應年級功能](../admin-courses/jin-jie-she-ding/ti-mu-she-ding.md#ru-he-da-kai-shi-sheng-zhang-hao-guan-li-de-wan-jia-nian-ji-de-gong-neng-bing-she-ding-ti-mu-dui-yin)，則其攻擊力會降低
{% endhint %}

### 遊戲角色的角色數值為何？ <a href="#zu-bie-shi-shen-me" id="zu-bie-shi-shen-me"></a>

<table><thead><tr><th width="212">角色</th><th width="86">蜜雅</th><th width="89">麻呂</th><th width="85">巴塔爾</th><th width="81">蘇菲</th><th width="83">卡希娜</th><th>亞弭爾</th></tr></thead><tbody><tr><td>部族</td><td>神鷹</td><td>巨蜥</td><td>狂狼</td><td>羚羊</td><td>靈貓</td><td>獵豹</td></tr><tr><td>類型</td><td>冒險家</td><td>守護者</td><td>鬥士</td><td>牧師</td><td>弓箭手</td><td>外交官</td></tr><tr><td>生命 -> 土地血量</td><td>100%</td><td>120%</td><td>105%</td><td>100%</td><td>100%</td><td>100%</td></tr><tr><td>能量 -> 能量上限</td><td>100%</td><td>100%</td><td>100%</td><td>100%</td><td>110%</td><td>120%</td></tr><tr><td>攻擊 -> 攻擊力</td><td>100%</td><td>100%</td><td>120%</td><td>100%</td><td>100%</td><td>100%</td></tr><tr><td>回復 -> 能量回復速度</td><td>100%</td><td>110%</td><td>100%</td><td>120%</td><td>100%</td><td>100%</td></tr><tr><td>財富 ->產 Pa 幣的速度</td><td>120%</td><td>100%</td><td>100%</td><td>105%</td><td>100%</td><td>110%</td></tr><tr><td>功勳 -> 答題賺 Pa 幣</td><td>110%</td><td>100%</td><td>100%</td><td>100%</td><td>120%</td><td>100%</td></tr></tbody></table>

{% hint style="info" %}
不同於一般地圖，競賽之盾與電競賽事、奪寶信號相同，其角色數值都是有經過「調整」的，詳情請見[此連結](jing-sai-zhi-dun-cao-zuo.md#zu-bie-shi-shen-me)
{% endhint %}

[^1]: 等級除以一百後，四捨五入至小數點第二位
