# みがわり AR Experience

A-FrameとAR.jsを使用して作成された拡張現実体験（AR）のためのサンプルコード

## コードの概要

1. **HTML Document:**
   - `index.html` はAR体験のメインのHTMLファイル

2. **A-Frame and AR.js:**
   - A-FrameとAR.jsのスクリプトが `<head>` セクションに組み込まれている

3. **3D Model:**
   - 3DモデルはA-Frameのアセットとして定義され、`assets/Substitute/ob0226_00.glb`から読み込まれる

4. **Marker:**
   - `.patt`ファイルを使用してマーカーが定義され、特定のパターンが検出されたときに3Dモデルが表示される

5. **Camera:**
   - A-Frameの `<a-entity camera></a-entity>` を使用してカメラがシーンに追加されている

## 実行
この[ページにアクセス](https://ryougafunashi.shop/)し、下記QRコードを認識させてください

## 注意事項

- ブラウザがWebXRやWebARに対応していることを確認してください。
