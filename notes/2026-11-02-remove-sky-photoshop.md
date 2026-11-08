# Photoshopで空を消す正しい方法

- 投稿者: @gfx.om
- 元投稿: https://www.instagram.com/reel/DezPPTVTN5A/
- 素材: 青空を背にした東京タワー

悪い例: Magic Wand ではエッジに残りが出る（赤い×印）。

正しい方法:
1. Channels パネルで Blue チャンネルを複製（コントラストが最も高い）
2. Image > Adjustments > Levels（Ctrl+L）で黒側・白側スライダーを寄せ、タワー＝黒／空＝白の硬いマスクを作る
3. チャンネルを選択範囲として読み込む
4. RGB に戻り、レイヤーマスクとして適用

結果: 透明背景へのきれいな切り抜き。
