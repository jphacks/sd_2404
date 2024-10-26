# QuickScribe
[![IMAGE ALT TEXT HERE](https://jphacks.com/wp-content/uploads/2024/07/JPHACKS2024_ogp.jpg)](https://www.youtube.com/watch?v=DZXUkEj-CSI)

## 製品概要
### 背景(製品開発のきっかけ、課題等）
数学の学習や研究において、多くのユーザーは手書きで数式や計算を記録したいと考えていますが、従来の入力方法は特にマウスでの手書き入力が難しく、数式変換に手間がかかります。これを解決するために、手書きの数学内容を自動で認識して計算結果に変換できるアプリケーションを開発しました。
### 製品説明（具体的な製品の説明）
本アプリケーションはマウスを使った手書き入力に対応しており、Google AI StudioのGemini-1.5-Flashモデルを使用して手書きの数学式を認識します。その後、MathJaxを用いて標準的な数学式にリアルタイムで変換して表示します。ユーザーはマウスで方程式や数学の問題を書き、システムが自動で認識して変換後の数式や計算結果を提供します。教育、研究、および学習ノートのシーンに適しています。
### 特長
#### 1. 手書き認識に対応
手書き入力でも、数式や内容を高精度で認識し、入力のハードルを下げます。
#### 2. リアルタイム数式レンダリング
MathJax技術を活用して、認識された数式を即時に画面上に表示し、ユーザーが確認および編集しやすくします。
#### 3. シンプルで直感的なユーザーインターフェース
ReactとTailwind CSSをベースにした直感的なデザインにより、マウスでの手書き入力がスムーズに行えます。

### 解決出来ること
### 今後の展望
### 注力したこと（こだわり等）
* 
* 

## 開発技術
### 活用した技術
#### API・データ
* Google AI Studio API：Gemini-1.5-Flashモデルを使用して手書きの数学式を認識し、計算式や結果に変換します。
* MathJax：数学式をウェブ上で表示可能な形式にレンダリングするために使用。

#### フレームワーク・ライブラリ・モジュール
* React：フロントエンドフレームワークで、ユーザーインターフェースの構築に使用。
* TypeScript：コードに型チェックを提供し、コードの品質を向上。
* Vite：高速なビルドツールで、開発速度と効率を向上。
* Tailwind CSS：スタイル管理に使用され、レスポンシブデザインをサポート。
* FastAPI：バックエンドAPIの開発およびフロントエンドとの連携に使用。
* PostCSS：CSSの前処理と最適化に使用。
* ESLint：コードの静的解析と構文チェックに使用。

#### デバイス
* PC：アプリケーションの開発およびテストに使用する主なプラットフォーム。

### 独自技術
#### ハッカソンで開発した独自機能・技術
* Google AI StudioのGemini-1.5-Flashモデルを使用した手書き認識に加え、結果をMathJaxを使ってリアルタイムで数式として表示するカスタムパイプラインを開発。これにより、手書きされた内容がスムーズに数式へと変換されるプロセスを実現。

