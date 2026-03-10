# 🟥 OCI 認定試験 模擬問題集 Vol.2

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success?logo=github)](https://hishibashi1001-bit.github.io/oci-quiz/)
[![OCI Foundations](https://img.shields.io/badge/1Z0--1085--25-30問-blue)](./foundations-vol2.html)
[![OCI Architect](https://img.shields.io/badge/1Z0--1072--25-25問-red)](./architect-vol2.html)

Oracle Cloud Infrastructure 認定試験対策の**ブラウザ完結型模擬問題集**です。  
Vol.2 では Foundations・Architect Associate それぞれの応用問題を新規収録しています。

🌐 **Live → https://hishibashi1001-bit.github.io/oci-quiz/**

---

## 📋 収録内容

| 試験 | コード | 問題数 | カバー範囲 |
|------|--------|--------|-----------|
| OCI Foundations Vol.2 | 1Z0-1085-25 | 30問 | ネットワーク・セキュリティ・IAM・ストレージ・ガバナンス・アーキテクチャ |
| OCI Architect Associate Vol.2 | 1Z0-1072-25 | 25問 | LB・FastConnect・DRG v2・Block Volume・OKE・Functions・Resource Manager |

## ✨ 機能

- **カテゴリフィルタ** — 苦手分野のみ集中学習
- **シャッフル出題** — 毎回異なる問題順
- **間違えた問題だけ再挑戦** — 弱点克服モード
- **即時フィードバック** — 解説付きで理解を深める
- **外部依存ゼロ** — HTML 単体で動作（オフライン可）

## 🛠 技術スタック

```
HTML5 / CSS3 / Vanilla JavaScript
外部ライブラリ: なし（CDN依存なし）
ビルドツール: なし（静的HTML）
デプロイ: GitHub Pages（Actions自動デプロイ）
```

## 🚀 デプロイ構成

```
main ブランチへの push
    └─ GitHub Actions (.github/workflows/deploy.yml)
           └─ gh-pages ブランチに自動デプロイ
                  └─ GitHub Pages で公開
```

## 📁 リポジトリ構成

```
oci-quiz/
├── index.html              # トップページ（問題集一覧）
├── foundations-vol2.html   # Foundations 1Z0-1085 Vol.2（30問）
├── architect-vol2.html     # Architect Associate 1Z0-1072 Vol.2（25問）
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages 自動デプロイ
└── README.md
```

## 👤 作成者

**石橋 英樹（Hideki Ishibashi）**  
FutureRays / インフラエンジニア  
OCI 12冠・AWS 4冠保有

- JR東海 J-Net6世代インフラ再設計プロジェクト（JR東海→JTIS→NTTデータ→NTTデータ東海→システムリサーチ→フューチャーレイズ）
- 上位工程（要件定義・基本設計）・クラウド（AWS/OCI）専門

## 📜 免責事項

本問題集は個人の学習目的で作成したものです。  
Oracle 公式の問題集・試験内容とは異なる場合があります。  
試験対策には Oracle 公式の学習教材も必ずご確認ください。
