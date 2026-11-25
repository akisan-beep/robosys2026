# plusコマンド
![test](https://github.com/takuto@melchior/robosys2026/actions/workflows/test.yml/badge.svg)
↑ テスト結果を反映したバッジの画像が埋め込まれる

標準入力から読み込んだ数字を足す。

（ここに前ページの項目をいろいろ書く）

## 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.10〜3.14

## テスト環境
- Ubuntu 24.04 LTS

## ライセンス
- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
- © 2026 Taro Suzuki
## warikan コマンド

金額を人数で割り、1人あたりの金額と余りを表示します。

### 使い方

./warikan 金額 人数
### 実行例

```bash
./warikan 3980 3
```

出力:

```text
1人あたり: 1326円
余り: 2円
```

### テスト

```bash
bash test.bash
```
