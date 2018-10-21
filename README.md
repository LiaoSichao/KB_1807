# カンファリン　(conf ×　　LINE)　

[![Product Name](image.png)](https://www.youtube.com/watch?v=G5rULR53uMk)

## 製品概要
### Conf　×　Tech　(会議×Tech)

### 背景（製品開発のきっかけ、課題等）

・議論の最中に議題を見失ってしまうことや，終わってすぐには会議内容を整理できないことが多々あった．

・議事録を作成するには，手書きでの文字起こしや文字の入力などの手間がかかる．また，現在のlineやgoogleの音声入力では，デバイス操作が煩雑である．

　→したがって，それらを解決できるように試みた．
### 製品説明（具体的な製品の説明）

音声の入力が発生したときに，リアルタイムかつキリの良いタイミングでテキストに変換していく．変換したテキストをLINEのグループに出力する

### 特長
#### 1. 会話内容をすぐにテキストに変換するため，いつでも今までの会話内容を随時確認できる．
#### 2. 発言が一旦終わった時にテキストに変換するので，普通に会話をしているだけで会話内容は作成でき，会議の際に操作の手間が必要ない．
#### 3. 複数人の使用でも，発話者の特定が容易である．

### 解決出来ること

リアルタイムで会話ログを確認できることとユーザーの操作の負担を大幅に軽減できる

### 今後の展望

今後試みたいこととして，時間をおいて議事録を見返した際に，思い出しやすくしたい．そのために会話内容のテキストデータから，その会議の雰囲気を数値で表現したい．例えば，テキストから会議において時間ごとの雰囲気をネガティブポジティブ度で判定する．
改善としては，リアルタイム録音での動作が不安定なので，安定的に実行できるようにしたい．
## 開発内容・開発技術
### 活用した技術
#### API・データ
今回スポンサーから提供されたAPI、製品などの外部技術があれば記述をして下さい。

*AWS

*Google Cloud platform

*LINEAPI

#### フレームワーク・ライブラリ・モジュール
*pyaudio

#### デバイス

*パソコン

*スマートフォン

### 研究内容・事前開発プロダクト（任意）
*研究内容:日本の古典におけるくずし字の自動認識を研究しています　

### 独自開発技術（Hack Dayで開発したもの）
#### 2日間に開発した独自の機能・技術
*音声のリアルタイムでの会話ログの送信に力をいれました
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください（任意）
