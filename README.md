## 研究実施計画 (Provisional Schedule)

※ 本計画は進捗状況により適宜見直しを行う。

```mermaid
gantt
    title 卒業研究スケジュール（仮）
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d

    section 1. 調査・設計
    先行研究の精読と課題抽出   :a1, 2026-04-13, 14d
    システム要件定義・詳細設計 :a2, after a1, 14d

    section 2. システム開発
    Keycloak SPI 開発環境構築 :b1, 2026-05-11, 14d
    SSSシェア管理機能の実装    :b2, after b1, 21d
    WebAuthn連携フローの構築   :b3, after b2, 35d

    section 3. 実験・修正 (10月重点)
    プロトタイプ動作確認       :c1, after b3, 14d
    評価実験(可用性・耐性テスト):c2, 2026-09-15, 30d
    実験結果に基づくシステム改善 :c3, 2026-10-15, 30d

    section 4. 成果まとめ
    評価データの集計・分析     :d1, 2026-11-15, 14d
    卒業研究報告書 本執筆      :d2, 2026-12-01, 45d
    口頭発表準備              :d3, after d2, 14d
