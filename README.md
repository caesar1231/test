# Setup

## トークン生成
Personal access tokens を生成し、以下の権限を付与する

- Actions(read, write)
- Contents(read, write)
- Pull requests(read, write)
- Variables(read, write)

## 変数設定
以下のシークレット・環境変数をセットする

シークレット
- PAT
 上記手順で生成したトークン

環境変数
- RELEASE_LABEL
 定期リリース番号（R23など）

## ブランチ保護
developとmainの削除をできないよう保護する

# 今後
- 自動プルリク機能追加
- develop rebaseプルリク追加
