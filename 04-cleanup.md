# 4. 後片付け

ハンズオン終了後、不要な費用が発生しないように以下を見直しましょう。

- Flux アプリの無効化または削除
  ![Fluxアプリの削除](./image/04-01.png)

  > ⚠️ Flux アプリを削除すると、SORACOM API アクションで使用している SAM ユーザー（`FluxAction-SoracomApi-getDataEntries1`）も一緒に削除されます。削除を避けたい場合は、事前に SAM ユーザーの「認証設定」>「SORACOM リソース認証」を解除しておいてください。

- 自分の SIM グループの簡易位置測位機能・Harvest Data の OFF
  ![簡易位置測位機能OFF](./image/04-02.png)
  ![Harvest DataOFF](./image/04-03.png)

---

[← 3. SORACOM Flux アプリを作成して動かす](./03-flux-app.md) ｜ [目次](./README.md) ｜ [参考リンク →](./05-references.md)
