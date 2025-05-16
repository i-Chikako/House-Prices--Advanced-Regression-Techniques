# House Prices - Advanced Regression Techniques - Kaggleコンペティション

このリポジトリは、Kaggleの「House Prices - Advanced Regression Techniques」回帰コンペティションに取り組んだ内容をまとめたものです。  
[https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## 🏆 結果
- 最終順位：4,671チーム中 652位（リーダーボード、2025年5月16日時点）
- 使用モデル：スタッキング（ベースモデル：LightGBM + XGBoost + CatBoost + GradientBoostingRegressor メタモデル：Ridge）
- 評価指標：Root Mean Squared Error（RMSE）
- 最終スコア：0.12509

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
- 複数モデルによるスタッキング

## 📁 ファイル構成
- `notebooks/HousePrices-sec.ipynb`: 最終モデルのNotebook

## 📝 補足
このコンペティションを通して、回帰問題の扱い方や評価指標（RMSE）、モデルのスタッキング技術について実践的に学ぶことができました。  
前処理がモデルの精度に大きく影響することを実感でき、特徴量が多いものを扱う際の大変さを理解することができました。
今後、特徴量の主成分化などほかの手法を用いて次元を削減した場合の、結果への影響も試してみたいと思いました。
