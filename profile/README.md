# AEGIS

**AEGIS（イージス）** は、地震・津波・天気の情報をひと目で把握できる防災アシスタントです。
この組織は AEGIS の各実装をまとめた開発組織です。

- 🌐 Web 版: https://bosai.vercel.app（[mabu-works](https://github.com/mabu-works) で公開）
- 👤 開発者: [@i-mabu](https://github.com/i-mabu)
- 🤖 Bot の組織: [@mabu-bots](https://github.com/mabu-bots)

## 実装一覧

| 実装 | リポジトリ | 内容 |
|---|---|---|
| Android 版 | [aegis-android](https://github.com/aegis-app/aegis-android) | 地震・津波・天気を地図で確認できる Android アプリ（v1.8.0、公開リポジトリ） |
| Java 版 | aegis-java | デスクトップ向け Java 実装（v1.5.4） |
| Windows 版（Java） | aegis-windows | Windows 向け Java GUI（v1.5.3） |
| Windows 版（C#） | aegis-windows-cs | Windows 向け C# / WinForms 実装（v1.2.3） |
| Python 版 | aegis | Python 実装（v1.4.3） |
| Discord Bot | aegis-discord-bot | 地震・津波・天気を Discord に知らせる Bot（本体はこの組織、運用側のフォークが mabu-bots にあります） |

## データについて

- 地震・津波情報: P2P地震情報 / 気象庁
- 天気: Open-Meteo
- 地図: 国土地理院タイル（雨雲レーダーは RainViewer）

## 方針

- 「実用的に使える防災アプリ」を目指し、情報はひと目で分かる表示を優先します
- リポジトリは Android 版のみ公開、他は非公開です
