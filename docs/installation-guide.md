# 導入手順

## Closed alpha

1. GitHub Release `v0.1.0-alpha.1` を開く。
2. `dist/budget-recipe-personal-crm-docs.zip`、`docs/manual-test.md`、`docs/strict-manual-test-addendum.md` を取得する。
3. repo を clone する。

```powershell
git clone https://github.com/Sunmax0731/budget-recipe-personal-crm.git
cd budget-recipe-personal-crm
cmd.exe /d /s /c npm test
```

## 実行

```powershell
node src/cli/index.js samples/representative-suite.json
```

WebApp は `public/index.html` を静的ホスティングできる構成です。AndroidApp と AdobePlugin は閉域アルファでは設計、責務分割、代表データ、自動検証、手動テスト手順を配布対象にします。
