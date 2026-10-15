# skill_kato_DEU

Salesforce／国民CRM関連のCodexスキル集です。

## 収録スキル

- `jfc-customization-unit-test-spec` — Salesforceカスタマイズ設計書から単体テスト仕様書を作成・改訂
- `jfc-flow-unit-test-spec` — 画面フローを除くSalesforce Flowの単体テスト仕様書を作成・改訂
- `salesforce-flow-playwright-ut` — 非画面Salesforce Flowのテスト自動化とケース別証跡作成
- `salesforce-playwright-ut` — Salesforce Sandboxで入力規則・数式をPlaywrightにより検証し、Excel証跡を作成

## インストール

必要なスキルフォルダーをCodexのスキルディレクトリへコピーします。各フォルダーの`SKILL.md`がエントリーポイントです。

Windowsの例:

```powershell
Copy-Item -Recurse -LiteralPath ".\skills\jfc-flow-unit-test-spec" -Destination "$env:USERPROFILE\.codex\skills\jfc-flow-unit-test-spec"
```

## 取り扱い

- Salesforceの組織ID、レコードID、ユーザー名、認証情報、ブラウザープロファイル、実行証跡はコミットしないでください。
- `salesforce-playwright-ut`の案件固有値はローカルの`automation/config/local.json`に設定し、実行前に対象組織と今回の許可範囲を確認してください。
- スキルはSalesforce設定の変更、Flowの配備・有効化、未承認のレコード削除を許可するものではありません。
