# プロジェクトセットアップガイド 

Scroll down to see english setup guide

## 前提条件
このプロジェクトを実行する前に、以下のものがインストールされていることを確認してください：
- [Node.js](https://nodejs.org/)（フロントエンド開発に必要）
- [Python](https://www.python.org/)（バックエンドサーバーに必要）

## 始めに

以下の手順に従って、バックエンドとフロントエンドの両方のサーバーを起動します：

### バックエンドのセットアップと起動
1. ターミナルを開き、バックエンドディレクトリに移動します。`/path/to/back-end` をバックエンドが保存されている実際のパスに置き換えてください：
    - `cd /path/to/back-end`
2. Python仮想環境を有効化します（仮想環境が事前にセットアップされていることを確認してください）：
    - Windowsの場合: `.\venv\Scripts\activate`
3. バックエンドサーバーを起動します：
    - `python main.py`

### フロントエンドのセットアップと起動
1. 新しいターミナルを開き、フロントエンドディレクトリに移動します。`/path/to/front-end` をフロントエンドが保存されている実際のパスに置き換えてください：
    - `cd /path/to/front-end`
2. フロントエンドの開発サーバーを起動します：
    - `npm run dev`

### プロジェクトにアクセス
両方のサーバーが起動したら：
- ブラウザを開き、フロントエンドサーバー用のターミナルに表示されているアドレス（通常は `http://localhost:xxxx` の形式）にアクセスします。実際のポート番号（`xxxx`）はターミナル出力に表示されます。


# Project Setup Guide

## Prerequisites
Before running this project, please ensure that the following are installed:
- [Node.js](https://nodejs.org/) (required for front-end development)
- [Python](https://www.python.org/) (required for back-end server)

## Getting Started

Follow these steps to start both the backend and frontend servers:

### Set Up and Start the Backend
1. Open a terminal and navigate to the backend directory. Replace `/path/to/back-end` with the actual path where your backend is stored:
    - ` cd /path/to/back-end`
2. Activate the Python virtual environment (ensure the virtual environment is set up in advance):
    - On Windows: `.\venv\Scripts\activate`
3. Run the backend server:
    - `python main.py`

### Set Up and Start the Frontend
1. Open a new terminal and navigate to the frontend directory. Replace `/path/to/front-end` with the actual path where your frontend is stored:
    - `cd /path/to/front-end`
2. Run the frontend development server:
    - `npm run dev`

### Access the Project
Once both servers are running:
- Open your browser and go to the address displayed in the terminal for the frontend server, usually in the format http://localhost:xxxx. The actual port (xxxx) will be shown in the terminal output.



