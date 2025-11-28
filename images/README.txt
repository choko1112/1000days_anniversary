【画像フォルダの使い方】

このフォルダに思い出の写真を配置してください。

ファイル名の例：
- photo-01.jpg
- photo-02.jpg
- photo-03.jpg
...など

HTMLファイルの中で以下のように参照されています：
<img src="images/photo-01.jpg" alt="2023年1月の思い出">

写真を追加する場合：
1. 写真をこの images フォルダに保存
2. index.html の該当する記録に以下を追加：

<div class="memory-image">
    <img src="images/あなたのファイル名.jpg" alt="説明文">
</div>

写真が不要な記録には、memory-image部分を省略してください。
