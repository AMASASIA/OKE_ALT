
# OKE_ALT_FULL - NFT/SBT Issuer DApp

## 📌 概要 / Overview

OKE_ALT_FULL は Next.js ベースの Web3 アプリです。Sepoliaネットワーク上で NFT + SBT を同時発行し、TokenBoundAccount（ERC6551）にも対応しています。  
This is a full-featured Web3 DApp built with Next.js. It supports minting both NFT & SBT on Sepolia and integrates ERC-6551 Token Bound Accounts.

---

## 🚀 起動方法 / Getting Started

### 🔧 ローカル実行 / Local Setup

```bash
git clone [this_repo]
cd OKE_ALT_FULL
cp .env.local.example .env.local
npm install
npm run dev
```

### 🌐 Vercelデプロイ / Vercel Deployment

- [ ] Vercelで新規プロジェクト作成
- [ ] 環境変数 `.env.local` を設定
- [ ] `npm run build && npm start` 自動ビルド

---

## 📁 主なファイル構成 / Main Files

| ファイル | 説明 |
|---------|------|
| `pages/index.js` | メール入力＋ウォレット接続＋Mint処理UI |
| `components/WalletUI.js` | ウォレットUI構成 |
| `contracts/SampleContract.json` | NFT/SBTスマートコントラクトABI |
| `.env.local.example` | 環境変数テンプレート |
| `README.md` | セットアップ手順（日英併記） |
| `package.json` | 起動スクリプト・依存定義 |

---

## 🛠 スマートコントラクト仕様 / Contract Features

- 🪙 `mint(address)` → NFT/SBT 同時発行
- 🧠 `ERC6551Registry.createAccount(...)` → Token Bound Account 作成
- 📩 メールUIでユーザー識別対応

---

## ✅ 対応環境 / Requirements

- Node.js v16+
- MetaMask (browser wallet)
- Sepolia ETH (for testing)

---

## 📫 お問い合わせ / Contact

- Author: AMASASIA  
- Mail: [info@amas.asia]
