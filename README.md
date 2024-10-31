# はんそくカナ打ち (For Japanese Kana Input on US keyboard at Mac)

![はんそくカナ打ちのマッピング](https://i.gyazo.com/85dbaad888de51c3c137c46cbbd520c7.png)

USキーボードに合わせて、カナの位置を調整したかな入力用配列です。「ATOK」並びに「ことえり」と組み合わせて利用することができます。

「ことえり」の配列を参考に<kbd>む</kbd> <kbd>ろ</kbd> <kbd>「</kbd> <kbd>」</kbd>の位置を調整してあります。USキーボードであってもJIS配列と大きく差分のないタイピングを実現できます。

また、同じUSキーボードでかな入力をする思想の『「はんそく」カナ配列』を取り入れてあります。

## 使用方法

Karabiner-Elements でキーマッピングを行います。[/karabiner/assets/complex_modifications/hansokukana.json](/karabiner/assets/complex_modifications/hansokukana.json)を`~/.config/karabiner/assets/complex_modifications/`に保存してKarabiner-Elementsでルールを有効化してください。

## 配列


### IME

前提として、ことえりの配列からマッピングを行います。

![ことえりのマッピング](https://i.gyazo.com/aab8bd778827dc43d334ab417b23dc05.png) ![ことえりのマッピング(Shift押し)](https://i.gyazo.com/66dffcac161632c219899cf18e474773.png)

### マッピング

基本的なマッピング

- <kbd>へ</kbd> → <kbd>む</kbd>
- <kbd>゜</kbd> → <kbd>へ</kbd>
- <kbd>」</kbd> → <kbd>「</kbd>
- <kbd>ー</kbd> → <kbd>」</kbd>
- <kbd>む</kbd> → <kbd>゜</kbd>
- <kbd>Shift + ほ</kbd> → <kbd>ー</kbd>

「はんそく」カナ配列からの引用

- <kbd>Shift + は</kbd> → <kbd>け</kbd>
- <kbd>Shift + ん</kbd> → <kbd>む</kbd>
- <kbd>Shift + そ</kbd> → <kbd>ろ</kbd>
- <kbd>Shift + く</kbd> → <kbd>へ</kbd>

### マッピング図

![はんそくカナ打ちのマッピング](https://i.gyazo.com/85dbaad888de51c3c137c46cbbd520c7.png)

![はんそくカナ打ちのマッピング(フルキー)](https://i.gyazo.com/235f468f148318d39452939bf7c065c0.png)

## 参考

- [「はんそく」カナ配列](https://cognitom.github.io/sankaku/archived/hansoku-jis.html)
