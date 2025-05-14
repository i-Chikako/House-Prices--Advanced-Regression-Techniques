# House Prices - Advanced Regression Techniques - Kaggleコンペティション

このリポジトリは、Kaggleの「House Prices - Advanced Regression Techniques」回帰コンペティションに取り組んだ内容をまとめたものです。  
[https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## 🏆 結果
- 最終順位：4,643チーム中 790位（リーダーボード、2025年5月14日時点）
- 使用モデル：スタッキング（LightGBM + XGBoost + CatBoost + Ridge など）
- 評価指標：Root Mean Squared Error（RMSE）

## 📄 概要
このコンペティションでは、アメリカ・アイオワ州の住宅価格を、物件の広さ・築年数・立地・設備といった特徴量から予測する回帰問題に取り組みました。

## 💻 開発環境
- Python 3.10  
- Jupyter Notebook  
- scikit-learn 1.6.1  
- XGBoost 3.0.0  
- LightGBM 4.6.0  
- CatBoost 1.2.8  
- pandas 2.2.2  
- numpy 1.26.4  
- matplotlib / seaborn（可視化用）

## 🔍 アプローチ
- 特徴量エンジニアリング（カテゴリ変数の処理、欠損値補完、スケーリングなど）
- クロスバリデーションを用いたモデル評価
- 複数モデルによるスタッキング（回帰モデルの組み合わせ）
- Log変換や正則化手法の工夫による性能向上

## 📁 ファイル構成
- `notebooks/HousePrices.ipynb`: 最終モデルのNotebook

## 📝 補足
このコンペティションを通して、回帰問題の扱い方や評価指標（RMSE）、モデルのアンサンブル技術について実践的に学ぶことができました。  
特徴量の前処理がモデルの精度に大きく影響することを実感でき、今後の分析業務やコンペ参加に活かしたいと思います。
