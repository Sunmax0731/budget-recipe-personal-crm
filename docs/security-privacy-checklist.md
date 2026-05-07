# Security / Privacy Checklist

## 方針

家計、食材、連絡先をローカルJSONで扱い、外部送信しない

## チェック

- [x] 外部送信をMVP外にした。
- [x] サンプルに実個人情報を含めない。
- [x] 手動テストで確認すべき権限を列挙。
- [x] release asset に手動テスト手順を添付。

## Android / Host 権限

- 追加のOS権限は閉域アルファMVPでは要求しない。

## Adobe 公式参照

- 対象ドメイン docs と created_idea metadata を優先。
