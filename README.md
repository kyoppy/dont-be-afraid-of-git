# こわくない 「確定申告」
## このテキストの目的
- 対象者
    - 確定申告を初めて行う人
    - 慣れていない人
    - 毎年やってるけど、よく分かってない人
- ゴール
    - 自分自身で確定申告が行えるようになる
    - 正しい節税で、確定申告における納税額を減らす
- GitHubで管理する理由
    - GitHubの差分管理を活用し、久しぶりに見たときに変更点を分かりやすくする
    - 記述が正しくない箇所をFork & pull-requestでみんなで改善していけるようにするため

## 確定申告の概要
- 確定申告とは?
    - 以下のことを行うイベント
        - 1.事業の収益を算出
        - 2.収益を元に、支払う所得税と消費税を算出
        - 3.所得税と消費税を支払う
- 確定申告の時期
    - 2月16日 ~ 3月15日 (土日祝の場合は翌営業日)
    - 所得税法 第120条 で定められている

- 1回の確定申告における領収書・請求書の有効期間 : 1月 ~ 12月
    - 【例】2025年3月に確定申告を行う場合 : 2024年1月 ~ 2024年12月

## 時期別のイベントリスト
|時期|イベント|
|:--|:--|
|**なるはや** ※やっていない人のみ|e-Taxのアカウント作成|
|1月 ~ 12月|領収書を会計システムに登録|
|1月 ~ 12月|収入を会計システムに登録|
|翌年 1月|税務署からの書類が届く ([解説](./content/zeimu.md#1月に税務署から届く資料))|
|翌年 1月 ~ 2月|会計システムで確定申告の資料を作成|
|翌年 2月中旬 ~ 3月中旬|e-tax経由で確定申告の資料を提出|

## 青色申告を行うメリット
- 青色申告特別控除 : 以下の1~5を全て満たすと、65万円の控除を受けられる
    - 1.事業所得の取引の記録方法 : 複式簿記 ([解説](./content/word.md#複式簿記))
    - 2.現金主義による所得計算の特例 : 選択していない ([解説](./content/word.md#現金主義による所得計算の特例))
    - 3.以下のいずれかを満たす
        - 確定申告の方法 : e-Tax ([解説](./content/e-tax.md))  **オススメ**
        - 仕訳帳と総勘定元帳の管理 : 優良な電子帳簿 ([解説](todo))
    - 4.事業所得 (個人事業主としての収入) : あり
    - 5.確定申告の期限 : 遵守している

## 控除
- 控除とは?
    - 所得税や住民税の負担を軽減する仕組み
- どうやって?
- 控除の種類
    - 所得控除 : 総所得から所得控除を差し引くことで課税対象額を現象させる
        |控除の種類|概要|
        |:--|:--|
        |[基礎控除](./content/word.md#基礎控除)|すべての納税者が受けられる控除|
        |[配偶者控除・配偶者特別控除](./content/word.md#配偶者控除)|配偶者(一定の所得以下)がいる場合の控除|
        |[扶養控除](todo)|扶養親族がいる場合の控除|
        |[医療費控除](todo)|1年間の医療費が一定額を超えた場合の控除|
        |[社会保険料控除](todo)|健康保険・年金などの支払い分を控除|
        |[生命保険料控除](todo)|生命保険や個人年金の支払い分を控除|
        |[地震保険料控除](todo)|地震保険の支払い分を控除|
        |[寄附金控除](todo)|ふるさと納税や特定の寄付をした場合の控除|
        |[小規模企業共済等掛金控除](todo)|小規模企業共済等掛金控除に支払った金額を全額控除にできる|
        |[青色申告特別控除](todo)|特定の条件を満たして青色申告を行った場合に受けられる控除|
    - 税額控除 : 計算された税額そのものを直接差し引く (所得控除より効果的)
        |控除の種類|概要|
        |:--|:--|
        |[住宅ローン控除](todo)|住宅ローンを利用して家を購入した場合に一定額を控除|
        |[配当控除](todo)|上場株式などの配当所得に対する税額控除|
        |[外国税額控除](todo)|海外で税金を支払った場合、日本の税額から控除|
        |[政党寄附控除](todo)|政党や政治団体への寄附をした場合に適用|
## 節税のHowTo
- 一般的な節税
    - 青色申告特別控除を活用することで、65万円の控除を受ける
- 経費に関する節税
    - todo
## Q&A
- ふるさと納税を行った場合、どこに何を登録すればよいか？
    - todo