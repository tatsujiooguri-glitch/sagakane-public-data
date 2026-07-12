# public-data｜読者が使える一次データ（CSV）

金利・還元率・マクロ等の一次データを、読者がそのまま使える形（CSV）で公開しています。
**単価（offer）などの守秘データは含めません**（公開するのは公的・公表の事実データのみ）。

## 使い方
- **ダウンロード**：下のリンクを開いて保存。
- **Googleスプレッドシートに自動取り込み**：セルに `=IMPORTDATA("<CSVのURL>")` と入力。

## データセット
| データ | CSV(raw) |
|---|---|
| 10年国債｜長期金利(10年応募者利回り) の推移 | https://raw.githubusercontent.com/tatsujiooguri-glitch/sagakane-public-data/main/macro-jgb-10y.csv |
| 日本銀行｜政策金利(誘導目標・上限) の推移 | https://raw.githubusercontent.com/tatsujiooguri-glitch/sagakane-public-data/main/macro-policy-rate.csv |
| 変動金利(標準優遇後)｜横比較 | https://raw.githubusercontent.com/tatsujiooguri-glitch/sagakane-public-data/main/mortgage-variable-standard.csv |

※ 数値は各更新時点のもの。変動・改定があります。利用時は各社公式で最新をご確認ください。