# kowake - 調剤用医薬品分譲願

調剤薬局で、他の薬局に医薬品の分譲 (小分け) を依頼する際の、分譲願いを簡単に作成できる Excel ファイルです。


## 説明 - Description

### ファイル - Files

[kowake.xlsx](https://github.com/Kimitsuna-Goblin/kowake/blob/master/kowake.xlsx) - 本体 (メイン) の Excel ファイルです。

[kowake.no-master.xlsx](https://github.com/Kimitsuna-Goblin/kowake/blob/master/kowake.no-master.xlsx) - 医薬品マスタが付属してないバージョンです。医薬品名や単価の検索はできません。消費税計算と合計計算はできます。医薬品名や単価を自分で入力したいときに使ってください。

[How-To-Use.mp4](https://github.com/Kimitsuna-Goblin/kowake/blob/master/How-To-Use.mp4) - 使い方の説明動画です。[YouTube](https://youtu.be/XuWe7ZRz2yQ) にも同じ動画があります (YouTube の動画は限定公開のため、検索はできません)。

[LICENSE](https://github.com/Kimitsuna-Goblin/kowake/blob/master/LICENSE) - ライセンスファイルです。本 Excel ファイルを再配布する場合は、必ず添付してください。

[README.md](https://github.com/Kimitsuna-Goblin/kowake/blob/master/README.md) - この README ファイルです。


## 動作環境 - Operating Environment

Windows 10 上の Microsoft Excel 2007、2016 で動作確認しています。

Excel Online では、残念ながら動作しません (2021年2月11日確認)。
医薬品名の絞り込みのために、リストのデータ入力規則に計算式を埋め込んでいますが、それに対応してないようです。


## 使用方法 - Usage

YouTube の [使い方の説明動画](https://youtu.be/XuWe7ZRz2yQ) を見てくださいww。


使い方の補足です。

+ 年月日は、ファイルを開いた当日の日付が表示されます。日付は書き換え可能です。

+ 自薬局の署名欄は、最初は架空の住所、薬局名、薬剤師名が入っていますので、書き換えて保存してください。
  [TEL] [FAX] の文字以外は書き換え可能です。

+ 医薬品マスタの先頭10行は予備欄です。予備欄は自由に編集できます。
  たとえば、軟膏容器の価格を予め設定しておきたい場合などに、予備欄をご利用ください。

例:
| 医薬品名          | ... | 金額    | ...
| :---------------: |:---:| :-----: | :---
| 軟膏容器５０g     | ... | 30      | ...
| 軟膏容器１００ｇ  | ... | 50      | ...
| 予備０３          | ... |         | ...
| 予備０４          | ... |         | ...

+ 誤操作防止の目的で、シートを保護していますが、パスワードは設定していません。
  シート保護を解除したいときは、ご自由に解除してください。
  ただし、シート保護を解除したファイルや、パスワードを設定したファイルを GitHub にアップロードしないでください。


### 医薬品マスタデータ - Data

+ 医薬品マスタのデータは、社会保険診療報酬支払基金 の 2023年6月30日 のデータをもとに作成しています。
  もし、薬価の誤りなどの問題点を発見されましたらお知らせください。


## ライセンス - License

[MIT](https://github.com/Kimitsuna-Goblin/kowake/blob/master/LICENSE)

本 Excel ファイルは、MITライセンスのもとで、基本的に自由に使用できます。

ただし、本 Excel ファイルの著作者および、医薬品マスターデータ提供者は、
当該ファイルを使用したために生じた損害、損失について、いかなる責任も負わないものとします。

なお、ファイルを再配布する場合は、必ず [LICENSE](https://github.com/Kimitsuna-Goblin/kowake/blob/master/LICENSE) ファイルを添付してください。

## 著作者 - Author

[Kimitsuna-Goblin](https://github.com/Kimitsuna-Goblin) (浦 公統; Ura Kimitsuna)

