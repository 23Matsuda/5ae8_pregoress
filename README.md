## 卒業研究スケジュール（ガントチャート）

```mermaid
gantt
    title 卒業研究進捗計画（2026年度）
    dateFormat  YYYY-MM-DD
    axisFormat  %m/%d

    section 調査・設計
    先行研究調査 (Split-key FIDO等) :a1, 2026-04-13, 14d
    システム要件定義・設計          :a2, after a1, 14d

    section 開発（Keycloak SPI）
    Keycloak環境構築・WebAuthn設定 :b1, 2026-05-11, 14d
    SSSライブラリの検証・導入      :b2, after b1, 14d
    カスタム認証プロバイダーの実装   :b3, after b2, 28d

    section 実験・評価
    マルチデバイス間での動作検証    :c1, after b3, 14d
    安全性・可用性の評価実験        :c2, after c1, 14d

    section 執筆
    中間報告書まとめ               :d1, 2026-06-20, 14d
    卒業研究報告書 本執筆          :d2, 2026-11-01, 45d
