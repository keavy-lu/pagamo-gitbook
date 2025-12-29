# 電競賽建議軟硬體與網路規格

### 軟硬體規格建議

**PC**

* 作業系統：
  * Windows：10+
  * macOS：10.15 (Catalina) 以上
* Browser: Google Chrome / Microsoft Edge（請更新至最新版本），中國用戶若非使用 Chrome / Edge 時，建議使用 360 / 百度 / 微信瀏覽器
* CPU: Intel Core i3 above
* Access Memory: 4GB or above&#x20;
* Hard Disk Drive: Any
* Graphics card: Intel HD Graphics above

**APP 規格**

* iOS: 13.0 以上 ( iOS 12 以下已有部分功能無法支援，例如：蘋果登入)
* Android: 9.0 以上

### 網路頻寬建議

* PaGamO 初次進入遊戲時，每人約會產生 20 MB 流量
* 初次載入完成後，進行遊戲的過程不需要太高的網路流量
* 若作答題目內含多媒體如圖片、音訊、影片等要計入流量
* 依每次活動作答之題目內容不同，PaGamO 工程端無法提供確切的現場網路頻寬需求，若題目內有多媒體內容，請與場地網路負責窗口確認，如「我們題目中包含 720p 影片，有可能現場所有人同時播放，要確保能順暢載入」

{% hint style="info" %}
現場路由設備連線品質是否穩定，可參考 現場網路環境檢測流程 進行測量
{% endhint %}

### 現場網路環境檢測流程

需要檢查此三項項目：PaGamO 連線穩定度、CDN 連線穩定度、CDN 下載速度，請依照以下方式進行檢測。

{% hint style="warning" %}
* 不要只用一台電腦測試，建議現場有多少台就同時開著多少，並將 ping 後面的參數提高，確認場地 Switch / AP 是否可以負荷比賽時的流量
* 可以搭配使用 [SpeedTest](http://www.speedtest.net/) ，但一定要測試 PaGamO 與 CDN 情境
{% endhint %}

#### PaGamO 連線穩定度檢測方法：**Linux / MacOS**

```
ping www.pagamo.org -c 100
```

上述指令會執行 100 次 ICMP，產生的結果會類似這樣：

```
64 bytes from 54.64.213.172: icmp_seq=0 ttl=238 time=43.706 ms
...(n times)
64 bytes from 54.64.213.172: icmp_seq=99 ttl=238 time=147.724 ms

--- www.pagamo.com ping statistics ---
100 packets transmitted, 100 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 136.646/147.036/247.131/20.507 ms
```

我們要看的資訊是最下面的一段：

```
100 packets transmitted, 100 packets received, 0.0% packet loss
```

表示送出了 100 個封包，收到了 100 個封包，封包遺失率 0.0%

```
round-trip min/avg/max/stddev = 136.646/147.036/247.131/20.507 ms
```

平均回應時間 「147.036ms」

#### PaGamO 連線穩定度檢測方法：Windows

```
ping www.pagamo.org -n 100
```

上述指令會執行 100 次 ICMP，產生的結果會類似這樣:

```
Relay from 54.64.213.172: bytes=32 time=52ms TTL 127
...(n times)
Relay from 54.64.213.172: bytes=32 time=52ms TTL 127

Ping statistics for 54.64.213.172:
    Packets: Sent = 100, Received = 100, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minumun = 52ms, Maximun = 52ms, Average = 52ms
```

我們要看的資訊是最下面的一段：

```
Packets: Sent = 100, Received = 100, Lost = 0 (0% loss)
```

表示送出了 100 個封包，收到了 100 個封包，封包遺失率 0.0%

```
Minumun = 52ms, Maximun = 52ms, Average = 52ms
```

平均回應時間 「52ms」

建議的數據為: 「封包遺失率 < 1%」 , 「平均回應時間 < 200ms」 ，超過這個數字都應該調整現場網路環境。

#### CDN 連線穩定度檢查方法：

檢查方法同 PaGamO 檢測方法，但把網址改為：

```
# Linux / MacOS
ping d32j6uwsrra4gx.cloudfront.net -c 100

# Windows
ping d32j6uwsrra4gx.cloudfront.net -n 100
```

#### CDN 下載速度檢測方法：Linux/MacOS

```
curl d32j6uwsrra4gx.cloudfront.net/assets/noto-sans-font/NotoSansTC-Regular-a884503e82e75e12747a73b1f79baebc9a0227a6f8c83137820df303f3cca842.woff2 -o /tmp/xxx.xx
```

輸出結果：

```
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 1814k  100 1814k    0     0  7044k      0 --:--:-- --:--:-- --:--:-- 7059k
```

看後面的 「Current Speed」，建議不要小於 500k

#### CDN 下載速度檢測方法：Windows

直接下載 [這個](https://global-cdn.pagamo.cn/assets/noto-sans-font/NotoSansTC-Regular-a884503e82e75e12747a73b1f79baebc9a0227a6f8c83137820df303f3cca842.woff2) 看看速度如何即可。
