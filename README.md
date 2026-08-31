# CursorでGPTが使えなくなる ― 理由と、11月までにやること

📊 [スライド資料はこちら（slides.html）](https://chaaaaarin.github.io/kawaru-channel-20260831/slides.html) | 📋 [1枚まとめ資料はこちら（onepager.html）](https://chaaaaarin.github.io/kawaru-channel-20260831/onepager.html) | 🎁 [プレゼントはこちら](https://chaaaaarin.github.io/gift-library/aa/)

---

## TL;DR（まず3行で）

- **OpenAI が、AI開発ツール「Cursor」への自社モデル（GPT系）の提供を打ち切ると発表**した。停止の予定日は **2026年11月12日**。
- **「CursorがGPTを外した」のではなく、OpenAI側が契約を解約した**。引き金は、イーロン・マスクの **SpaceX が Cursor を買収した**こと。
- **影響は Cursor の中だけ・利用の約5%**。ChatGPT や他ツールには関係なし。Cursorで GPT を使っている人は、11月までに乗り換え等の準備をすれば困らない。

確度マーク: ✅ 公式確認済み ／ 🔶 一次情報あり（金額など報道ベース）

---

## もくじ

- [1. Cursor とは / これまでの Cursor](#1-cursor-とは--これまでの-cursor)
- [2. 何が起きたのか（時系列）](#2-何が起きたのか時系列)
- [3. 「追い出した」のは OpenAI 側](#3-追い出したのは-openai-側)
- [4. なぜ OpenAI はそこまでしたのか](#4-なぜ-openai-はそこまでしたのか)
- [5. あなたに影響はあるか](#5-あなたに影響はあるか)
- [6. 11月までにやること（4つ）](#6-11月までにやること4つ)
- [7. Cursor は弱くなるのか](#7-cursor-は弱くなるのか)
- [8. 教訓：1社依存の外し方](#8-教訓1社依存の外し方)
- [9. FAQ](#9-faq)
- [今日からやること（始めるならこの順番）](#今日からやること始めるならこの順番)
- [まとめ](#まとめ)
- [プレゼント（無料）](#プレゼント無料)
- [動画内で補足する用語](#動画内で補足する用語)

---

## 1. Cursor とは / これまでの Cursor

**Cursor（カーソル）** は、AIがコードを書いてくれる開発ツール（エディタ）。世界中のエンジニアが使っている。

特徴は、**AIの頭脳（モデル）を自分で選べる**こと。GPT（OpenAI）・Claude（Anthropic〈アンスロピック〉）・Gemini（Google）・Grok（xAI〈エックスエーアイ〉）・Composer（Cursor自社）を、同じ画面で切り替えて使える。「今日はGPT、明日はClaude」と、**1社に縛られずに使える**のがCursorの売りだった。✅（[Cursor公式ヘルプ「Available models」](https://cursor.com/help/models-and-usage/available-models)）

今回、その「選べる自由」の一角が崩れる。

---

## 2. 何が起きたのか（時系列）

| 日付 | 出来事 | 確度 |
|---|---|---|
| 2026年6月16日 | SpaceX が Cursor（開発元 Anysphere〈エニスフィア〉）の買収で合意と報道 | 🔶 報道 |
| 2026年7月8日 | Grok 4.5 が Cursor 全プランに搭載 | ✅ [Cursor公式ブログ](https://cursor.com/blog/grok-4-5) |
| 2026年8月14日 | SpaceX が買収を正式完了。Cursor は「SpaceXAI」部門へ | ✅ [Cursor公式X](https://x.com/cursor_ai/status/2088249881718919393) |
| 2026年8月28日 | OpenAI が契約打ち切りを発表（ブログ公開） | ✅ [OpenAI公式ブログ](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/) |
| 2026年8月29日 | OpenAI公式Xで告知（表示1,475万）／Cursor CEO が反応（表示585万） | ✅ |
| 2026年11月12日（予定） | Cursor から OpenAI モデルへの直接アクセスが停止 | ✅ ただし「提案」・交渉中 |

OpenAI公式ブログの原文（一部）：

> Today, we notified SpaceX that we intend to wind down our contract providing OpenAI models to Cursor, with a proposed shutoff date of November 12, 2026.

（訳：本日、SpaceX に対し、Cursor へ OpenAI モデルを提供する契約を段階的に終了する意向を伝えた。停止の予定日は2026年11月12日。）✅（[OpenAI公式ブログ](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)）

---

## 3. 「追い出した」のは OpenAI 側

よくある誤解と、実際：

| 誤解 | 実際 |
|---|---|
| Cursor が GPT を切り捨てた | **OpenAI が「もう Cursor には貸さない」と通告した** |
| Cursor が Grok だけにした | Cursor は「困る、話し合いたい」と反応している |

買収で持ち主が変わったとき、OpenAI は契約を解約できる条項があり、その権利を使った。

Cursor CEO の Michael Truell（マイケル・トゥルーエル）氏の投稿（一部）：

> OpenAI models serve about 5% of Cursor user traffic, and we're speaking with the OpenAI team to resolve this.

（訳：OpenAIモデルは Cursor の利用の約5%で、この問題を解決するため OpenAI と話し合っている。）✅（[Truell 氏の X 投稿](https://x.com/mntruell/status/2093532254006063557)）

**「11月12日」は確定ではない。** OpenAIの発表は「提案する停止日（proposed shutoff date）」という書き方で、両社は交渉中。ただし決裂すればその日で止まるため、準備は「止まる前提」で進めるのが安全。✅（[OpenAI公式ブログ](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)）

---

## 4. なぜ OpenAI はそこまでしたのか

OpenAI公式ブログが挙げた理由は主に3つ。すべて ✅（[OpenAI公式ブログ](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)）

1. **規約を守る保証がない** ― 買い手の SpaceX が、OpenAIの利用規約の範囲で技術を使う、と確信が持てない。
2. **過去に契約違反があった** ― マスク氏が買収した旧 Twitter、傘下の xAI が OpenAI の規約に違反した経緯がある（xAI の違反はマスク氏本人が宣誓下で認めたとされる）。
3. **新モデルは渡さない** ― 今後の新モデル（Astra〈アストラ〉）は Cursor に提供しない、と明言。

原文（一部）：

> We are making this choice because we cannot be confident that SpaceX will use our technology within our terms of service, based on our experience with Elon Musk's companies violating contracts.

（訳：この判断をするのは、マスク氏の会社が契約に違反してきた経験をふまえると、SpaceX が当社の技術を利用規約の範囲で使うと確信できないためだ。）

### 背景：なぜ SpaceX が Cursor を持っているのか

2026年8月14日、SpaceX が Cursor の開発元 Anysphere の買収を正式完了。Cursor は SpaceX 傘下の「SpaceXAI」部門に入った。✅（[Cursor公式X](https://x.com/cursor_ai/status/2088249881718919393)）
買収額は $60B（約9兆円）規模とされるが、これは各社報道による数字で、金額入りの一次発表は確認できていない。🔶

---

## 5. あなたに影響はあるか

3パターンで確認：

| パターン | 影響 | 対応 |
|---|---|---|
| ① Cursor を使っていない | なし | 不要 |
| ② Cursor で Claude / Gemini 中心 | ほぼなし | 既定モデルの確認だけ |
| ③ Cursor で GPT をよく使う | あり（11月12日〜） | 下の「4つ」を実施 |

**これは「Cursor の中だけ」の話。** 止まらないもの：ChatGPT（ふつうのチャット）／OpenAI の API を直接使う他のツール・アプリ／Cursor の Claude・Gemini・Grok・自社モデル／VS Code など他のエディタ＋GPT。
「GPTが世の中から消える」話ではなく、Cursor という1つのツールが GPT を卸してもらえなくなるだけ。

影響を受けるのは Cursor 利用者の **約5%**（＝OpenAIモデル ÷ Cursorの全利用。Cursor CEO 発言）。✅（[Truell 氏の X 投稿](https://x.com/mntruell/status/2093532254006063557)）

---

## 6. 11月までにやること（4つ）

### ① 使用モデルを確認する
Cursor の設定でモデル一覧を開き、ふだん選んでいるモデルが GPT 系かどうか見る。GPT 系なら「③に該当」で、対応が必要。

### ② 既定モデルを乗り換える

| 乗り換え先 | 立ち位置 | 備考 |
|---|---|---|
| Claude（Anthropic） | コード用途で定番 | もともと Cursor 利用の多数派 |
| Gemini（Google） | 今回の件と無関係 | そのまま使える |
| Grok（xAI） | Cursor 全プランに搭載済み | 2026年7月8日〜。SpaceXAI 製 ✅[出典](https://cursor.com/blog/grok-4-5) |

### ③ どうしても GPT が要るなら、自分の API キーを用意する
OpenAI で自分用の API キー（利用の窓口）を作り、Cursor に登録すると GPT を使い続けられる場合がある。料金は OpenAI に直接、使った分だけ支払う形。
**⚠️ ただし全機能はカバーされない**：自動補完・エージェント系など一部の機能は対象外とされ、停止後にどこまで動くかは OpenAI も Cursor も詳細を公表していない（2026年8月末時点）。

### ④ 記録を残す
GPT と作った大事なやり取り・生成物は手元に保存。よく使う指示文（プロンプト）はテキストで別に控える。「GPT前提の書き方」は、他モデルでも通る書き方に直しておく。

---

## 7. Cursor は弱くなるのか

**大きくは弱くならない見込み。** もともと GPT の利用は約5%で、乗り換え先も揃っている。

- Claude・Gemini は今までどおり
- Grok 4.5 は2026年7月8日から全プランに搭載済み ✅（[Cursor公式ブログ](https://cursor.com/blog/grok-4-5)）
- Cursor 自社モデル（Composer）もある

**ただし、こういう見方もある**（デメリット側）：GPT が抜けると選べる大手モデルが1つ減る／Cursor は SpaceXAI 傘下で、自社の Grok が推されやすい立場／「選べる器」だった Cursor が、少し1社寄りに見えてくる。

---

## 8. 教訓：1社依存の外し方

便利なツールでも、その中身（AIの頭脳）を1社に頼っていると、**会社どうしの都合で、ある日いきなり使えなくなる**ことがある。今回はそれが現実になった。

今日からできる3つの習慣：

1. **モデルは2社は使える状態に** ― メインとは別に、もう1社をいつでも選べるようにしておく。
2. **指示文を1社に寄せすぎない** ― 特定モデルの癖に最適化しすぎず、他でも通る書き方にする。
3. **定期的に手元に書き出す** ― 大事なやり取り・設定・プロンプトは自分の手元にも残す。

---

## 9. FAQ

**Q. 無料プランでも関係ありますか？**
A. OpenAI の発表はプランを分けず「Cursor 経由の直接アクセス」全体の話。✅（[OpenAI公式ブログ](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)）

**Q. 日本のユーザーも対象ですか？**
A. 地域は限定されていない。Cursor で GPT を使っているなら対象。

**Q. Grok に乗り換えて大丈夫？**
A. 用途しだい。品質は好みで試し、大事な作業は1社に固めない、が無難。

**Q. $60B の買収って本当？**
A. 買収完了は Cursor 公式が発表。金額は各社報道による数字で、一次発表は確認できていない。🔶

---

## 今日からやること（始めるならこの順番）

Cursor で GPT を使っている人向け：

1. いま自分が選んでいるモデルを確認する（**今日**）
2. 既定モデルを Claude / Gemini / Grok のどれかに変えて試す（**今週**）
3. GPT が必須なら、自分の API キーを用意する（**10月中**）
4. 大事なやり取り・プロンプトを手元に書き出す（**11月12日まで**）

---

## まとめ

- OpenAI が Cursor へのモデル提供を打ち切り、2026年11月12日に GPT が使えなくなる（予定）
- 影響は Cursor の中だけ・約5%。Claude / Gemini / Grok に乗り換えられる
- 教訓は「1社に頼りすぎない」。別の手をいつでも出せる状態にしておく

---

## プレゼント（無料）

「プレゼント図書館」から受け取れます → **https://chaaaaarin.github.io/gift-library/aa/**

1. **AIツール ロックイン診断アプリ** ― 数問に答えると「1社依存の度合い」を判定し、その人向けの分散プランを提示するミニアプリ。
2. **Cursorユーザーの11月前 やることチェックリスト** ― 使用モデルの確認 → 乗り換え → APIキー持ち込みの手順と限界 → 記録の残し方を、今日から手を動かせる形でまとめたチェックリスト。

---

## 動画内で補足する用語

| 用語 | かみ砕き |
|---|---|
| Cursor（カーソル） | AIがコードを書いてくれる開発ツール（エディタ） |
| Anysphere（エニスフィア） | Cursor を作っている会社。SpaceX が買収した |
| モデル / GPT系 | AIの頭脳本体。GPTはOpenAI、ClaudeはAnthropic、GeminiはGoogle、GrokはxAI製 |
| API（エーピーアイ） | ソフト同士をつなぐ窓口。Cursor は各社のAPI経由でモデルを呼ぶ |
| API キー | その窓口を使うための、自分専用のカギ（文字列） |
| 利用規約（ToS） | 使うときに守るルール。OpenAI は「守る保証がない」と主張 |
| ベンダーロックイン | 1社の製品に依存しすぎて、抜けられなくなる状態 |
| SpaceXAI | SpaceX 傘下の AI 部門。xAI・Grok・Cursor などを含む |
| Composer（コンポーザー） | Cursor の自社モデル |

---

*本資料は公開情報をまとめた非公式の解説です。最新の仕様・対応は各社の公式発表をご確認ください。*
