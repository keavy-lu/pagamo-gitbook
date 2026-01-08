---
description: 說明
---

# App 測試設定說明

## 測試裝置需連結公司 wifi

1. 要進入 develop, release 等環境時，裝置都需要使用 11 樓的公司 wifi。
2. 如有在家測試需求，可以額外設定 VPN。VPN 設定請得到部門主管核准後，再跟 Jeff Yeh 提出申請。

## 測試使用的 email

如有需要 Gmail 驗證可使用個人帳號，並提供給 Derek Nien 粘庭睿（RD App）

## iOS

1. 安裝 TestFlight / 下載測試版 App
2. iOS 裝置下載 TestFlight 並安裝
3. 收到測試邀請信以後，可在 TestFlight 下載：
   1. PaGamO Internal：內測版（預設連 develop 機，Sprint verifying 的票可以在 Internal 版測試到）
   2. PaGamO：正式版（通常 SprW2D2 以後是連 Release 機 / SprW2D5 會發連正式機的版本，後續上架用這版送審）\
      請先確認自己裝置連接公司 VPN 或 wifi，否則 PaGamO App 可能會因為連不到 develop / release 機器無法正常進入遊戲
4. 備註：每次有新的測試版 App，TestFlight 會推播通知，可下載更新（測試前請確認 PaGamO Internal App 是當前最新版本） (edited)

## Android

1. 打開 Google Play 內部測試功能：打開 Google Play App，按照[影片](https://bonio.slack.com/files/U0EV7MJ2K/F01GWTSEK9U/screen_recording_20201217-102224_google_play_store.mp4?origin_team=T0CT4H01E\&origin_channel=D07AKFPQVG9)的步驟，進入設定的地方 ，狂按最下方關於的「Play 商店版本」（至少 7 次），直到出現是否同意開啟的畫面（同意開啟）
2. 點這個[連結](https://play.google.com/apps/internaltest/4697457236897835271)加入「PaGamO - Internal」測試計劃
3. 測試計畫加入成功後，他應該就會轉到 Google Play 下載頁面，之後就跟一般 App 下載的方式一樣了

* 備註1：若後續需要下載新版 PaGamO - Internal，可在 Google Play 搜尋 PaGamO Internal 然後更新
* 備註2：PaGamO 正式版 與 PaGamO - Internal 版目前無法同時安裝（可能會安裝失敗），安裝前建議先移除舊版的 App
* 備註3：開啟 PaGamO - Internal 版（預設連 develop 機）前，請先確認自己裝置連接公司 VPN 或 wifi，否則 PaGamO App 可能會因為連不到 develop / release 機器無法正常進入遊戲



## App 當前環境須知：

1. PaGamO App 1.OOO.01 是連接 release 機器，1.OOO.02 以上都是連正式機
2. PaGamO Internal App 預設都是連 develop 機器，但點擊下方的「島嶼」圖片會彈出一個切換伺服器彈窗，可以再自行切換設定（選項不用調整直接使用）。

<figure><img src="../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

### 如果需要連到 pre-deploy 進行測試，該怎麼操作？

1. 使用 PaGamO Internal 內測版測試：
   1. 在上圖的右上角選擇「Production」
   2. 於最下欄將網址改為「https://pre-deploy.pagamo.org」
   3. 以正式機帳號進行登入
2. 使用 PaGamO 正式版（Beta 版）：遵循 [對話串](https://app.gitbook.com/u/SIrTH5y8tzfgcEL2OdRhmzsyKn73) 的步驟開啟下方面板，調整伺服器

### PaGamO Internal 與 PaGamO 正式版（Beta）版有什麼不同？

* PaGamO Internal 的內容比較新，可能包含這 SP 還沒有上線的功能、剛 merge 進 develop 但還沒有進 release 的功能。
* PaGamO 正式版（Beta 版）才會是這 SP 預計更新上線的功能

大多數時候，用 PaGamO Internal 即可測試一般功能，除非是一些比較特別的機制（例如：推播、universal link），牽涉到 App Bundle ID 設定，用 Internal / 正式版 測試才會有所不同。
