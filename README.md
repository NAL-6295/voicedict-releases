# VoiceDict Releases

macOS の menubar 常駐型音声入力アプリ **VoiceDict** の配布リポジトリです。
（ソースコードのリポジトリは非公開で、ここには配布物のみを置いています）

## ダウンロード

最新版は [Releases](https://github.com/NAL-6295/voicedict-releases/releases/latest) から
`VoiceDict-share.zip` をダウンロードしてください。

- 展開して `VoiceDict.app` を `/Applications` へコピー → ダブルクリックで起動
  （Developer ID 署名 + Apple ノータライズ済み。ターミナル操作は不要です）
- 動作要件や初回の権限設定は zip 同梱の `README-初回起動手順.txt` を参照

## 自動アップデート

v0.6.0 以降のアプリは Sparkle による自動アップデートに対応しています。
`appcast.xml` はそのフィードです（アプリが自動で参照します）。
