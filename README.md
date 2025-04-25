# predict_stock
職業訓練校にて作成した、pythonとStreamlitを使った株価予測ツールです。
Streamlitサイトにて公開しています。 =>
[リンク](https://predictstock-aacgmsfgrgfmpikmm6yjao.streamlit.app/)

## 使用技術（Tech Stack）
Python
Streamlit
scikit-learn
yfinance
Plotly（チャート描画用）

## 機能（Features）
指定銘柄の株価取得（yfinance）
終値・14日移動平均のグラフ表示
値動きの可視化（ラインチャート・ローソク足チャート）
線形回帰による株価予測（30日後）
予測値と実測値の比較チャート

## 注意事項（Caution）
本アプリの予測は、あくまで学習目的で作成されたものであり、実際の投資判断には使用しないでください。
また、本アプリを使用したことによるいかなる損失・損害にも責任を負いかねます。
