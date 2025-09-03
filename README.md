＃＃　プロジェクト概要

厚生労働省の統計データを用いて、日本の社会保険料の長期的な推移を分析する。 社会保険制度の持続が可能か、少子高齢化の影響について考察することを目的とする。



＃＃  データ出典
本分析で使用したデータは、e-stat(政府統計の総合窓口)

:厚生労働省 / 令和5年度社会保障費用統計
:https://www.e-stat.go.jp/stat-search/files?stat_infid=00004029808

＃＃　分析手順

１，Excelファイルを読み込む
２，年度ごとの社会保険料合計を可視化する
３，グラフの傾向を確認し、社会的要因と関連付けて考察する

＃＃　実行手順（Google Colab）
1. Google Colabを開く(https://colab.research.google.com/) 
2. このリポジトリの`portfolio.ipynb`をアップロードする 
3. 上から順番にセルを実行する
4. [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/longxishenzhi2-lang/japan-social-insurance/blob/main/portfolio.ipynb)



# 日本社会保険料の分析と考察

![保険料の推移グラフ](portfolio_graph.png)

#考察
：１９５１年から一貫して社会保険料は上昇している
:特に１９９０年代以降の高齢化の影響で急激に増加
：今後も少子高齢化が進むため、若者世代の負担が増加する可能性が高い

＃＃必要ライブラリ
以下のコマンドでまとめてインストールできます：

```bash
pip install -r requirements.txt


