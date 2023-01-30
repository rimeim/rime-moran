# 魔改自然碼 Rime 方案

個人自用魔改自然碼的 Rime 方案，簡稱「魔然」。

⚠ 方案設計仍處於實驗階段，方案本體亦仍在建設中，不代表最終品質。

本方案的主要特徵：

+ 開箱即用
+ 優先支持傳承字（繁體字）
+ 基於自然碼雙拼和輔碼
+ 主要面向大詞庫整句輸入用法
+ 支持輔碼造詞
+ 支持簡拼：jsjkxj -> 計算機科學家
+ 重新設計固頂一二級簡碼與簡詞（⚠ 仍在建設中）
+ 收 3 萬簡繁漢字
+ 內置 20 萬大詞庫（※ 亦可手動開啓搜狗百萬詞庫）

其他自定義功能：

+ 分號次選
+ 自定義短語
  - `moran.custom.txt`
+ 簡繁快速切換
  - Ctrl+S (S 意爲 simplified)
+ 虎碼反查
  - 用 `` ` `` 引導
+ 繪文字（Emoji）支持
  - 用 Ctrl+E 開關
+ Unicode 編碼和區位顯示
  - 用 Ctrl+U 開關
+ 時間快速查詢與輸入
  - 日期 orq
  - 星期 oxq
  - 節氣 ojq
+ 大寫數字/金額轉換
  - 用 `S` 引導，如輸入 `S123`
+ 日語和英語詞庫（默認禁用）

## 鳴謝

+ 自然碼原始碼表來自 [rime-zrm](https://github.com/bigshans/rime-zrm)
+ 部分功能設計得到[小鶴音形](https://flypy.com)的啓發
+ Lua 腳本和繪文字來自 [秃版虎碼 Rime 方案](https://tiger-code.com/)
+ 皮膚收集自
  - [ssnhd/Rime](https://github.com/ssnhd/rime/)
  - [KyleBing/rime-wubi86-jidian](https://github.com/KyleBing/rime-wubi86-jidian/)

大部分詞庫收集自其他 Rime 方案，出處均在相應詞典文件頭標出。

本方案的製作得到了 @铁圈 的幫助，在此表示感謝。
