# golf_competition

## 目的：ゴルフコンペの集計用notebook

コンペの集計およびハンデをペリア方式、ダブルペリア方式で計算できるものをjupyter notebookで実装しました。
注意点は下記の通りです。

- CSVはsampleの形式に従う
  - Name, HOLE1, ... ,HOLE18を参加者分記入する。
- ファイルパスの指定とモードの指定を行ってください。
  - 集計に違いがないか確認するために、途中でOUT、IN、GROSSを表示しています。
  - random_seedで乱数のシードを指定します。用途としては、誰かに好きな番号を選ばせることで、実行者が結果を意図的に操作できないようにするために作成しました。使いようによっては盛り上がると思います！
- あとはCSVのパスを指定し、Run Allを実施するだけ！
- 参加者が多すぎない場合はnotebook上で結果を確認できます！人数が置い場合は出力されたCSVを参照してください。
- 出力結果は、指定されたフォルダに「final_result.csv」とおいうファイル名で保存されます。
- その他、細かい点はnotebookにも説明を書いているので、そちらを参照してください！

（注意）
趣味で作ったこと、主に自分用で作っただけなので、高度な技術は一切使用していません。
もし使用される場合は、各個人の責任でお願い致します。
