# House Prices - Advanced Regression Techniques - Kaggleコンペティション

このリポジトリは、Kaggleの「House Prices - Advanced Regression Techniques」回帰コンペティションに取り組んだ内容をまとめたものです。  
[https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## 🏆 結果
- 最終順位：4,671チーム中 652位（リーダーボード、2025年5月16日時点）
- 使用モデル：スタッキング（ベースモデル：LightGBM + XGBoost + CatBoost + GradientBoostingRegressor メタモデル：Ridge）
- 評価指標：Root Mean Squared Logarithmic Error（RMSLE）
- 最終スコア：0.12509

## 📄 概要
このコンペティションでは、アメリカ・アイオワ州の住宅価格を、物件の広さ・築年数・立地・設備といった特徴量から予測する回帰問題に取り組みました。

## 💻 開発環境
- Python 3.12.3  
- Jupyter Notebook  
- scikit-learn 1.6.1  
- XGBoost 3.0.0  
- LightGBM 4.6.0  
- CatBoost 1.2.8  
- pandas 2.2.2  
- numpy 1.26.4  

## 🔍 アプローチ
- 特徴量エンジニアリング（カテゴリ変数の処理、欠損値補完、スケーリングなど）
- クロスバリデーションを用いたモデル評価
- 複数モデルによるスタッキング

## 📁 ファイル構成
- `notebooks/HousePrices-sec.ipynb`: 最終モデルのNotebook（最終モデル”meta_model”）
- `notebooks/HousePrices-first.ipynb`: 開発中の試行錯誤ノートブック

## 📝 補足
このコンペティションを通して、回帰問題の扱い方や評価指標（RMSE）、モデルのスタッキング技術について実践的に学ぶことができました。  
前処理がモデルの精度に大きく影響することや、特徴量の多いデータを扱う難しさも実感しました。
今後は、主成分分析などを使って次元削減を行い、その効果を検証してみたいと考えています。
