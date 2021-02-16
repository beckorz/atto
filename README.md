# atto

[atto](https://beckorz.github.io/atto/)

デスクトップスクラップツール

ボタン一つで画面の一部を切り抜き、最前面に表示させておくソフトです。
作業中に他のアプリケーションの一部を参照したい場合等に使用できます。
画面のスクリーンショットを取る際にも使えます。

P.S. 今は閉鎖され入手困難な、あるツールにインスパイアされ作成しました。元作者様感謝いたします。

高dpi対応、マルチディスプレイ対応しています。


## Purpose
パソコンで作業する際に、気になった情報を一時的にキープする事は案外面倒なものです。紙に書いたり、テキストエディタに貼り付けたりする煩わしい作業の軽減が目的です。
基本的には「情報キープ → 要らなくなれば破棄」という使い捨て感覚での使用がオススメです。
ノートパソコン等の狭い画面で作業する時などは特に便利に使えると思いますが、マルチディスプレイ時代の昨今でも有用な機能です。


## Requirement
- Windows XP Later (x86,x64)
- Visual Studio 2015 C++ Runtime

    ```
    コンピューターに MSVCP140.dll がないため、プログラムを開始できません。
    ```

    のようなエラーメッセージが表示された場合、MicrosoftからRuntimeをインストールして下さい。
    [Download Visual Studio 2015 の Visual C++ 再頒布可能パッケージ from Official Microsoft Download Center](https://www.microsoft.com/ja-JP/download/details.aspx?id=48145)


## Download
- [atto latest download](https://github.com/beckorz/atto/releases/latest)


## Usage

1. atto.zip を解凍
2. atto.exe を実行(タスクトレイに常駐します。)
   ![](./images/tasktray.gif)
3. 画面を切り取りたい時に、<kbd>Ctrl</kbd>+<kbd>1</kbd>キーを押すと、スクラップ化状態となります。
   この時、マウスカーソルが変化してスクラップ化準備である事を知らせます。
   ![](./images/prepare.gif)
    * ショートカットキーのデフォルト設定は Ctrl+1です。
      他のソフトで予約されている場合は使用できません。
4. スクラップ化準備状態で好きな箇所の好きな範囲を🖱マウスでドラッグします。
   ドラッグした範囲がスクラップ(切り抜き)として生成されます。
   ![](./images/scrap.gif)
5. スクラップされたウィンドウは、マウスでスクラップの移動も可能で、スクラップウィンドウが邪魔な場合、ダブルクリックでスクラップウィンドウサイズを縮小・拡大が行えます。また、スクラップウィンドウを終了する場合は、右クリックメニューの終了か、<kbd>ESC</kbd>キーで終了できます。
6. 必要に応じて、タスクトレイのメニューのオプションから設定変更可能です。
7. attoを終了する場合は、タスクトレイの右クリックメニューの終了から終了可能です。
   ![](./images/mainmenu.gif)

- アンインストール時には、レジストリを使用しておりませんので、そのまま削除して結構です。


## Other feature
- コンパクトサイズ  
    スクラップをダブルクリックすると、コンパクトなサイズへと瞬時に切り替わります。解除は再度ダブルクリックする事で行えます。
    スクラップが邪魔な時に使用します。

- スクラップの移動  
    マウスでドラッグして移動する事が可能ですが、カーソルキーでの移動も行えます。
    <kbd>shift</kbd>キーとの組み合わせで移動量が変化します。


## Third party software
- [jbeder/yaml-cpp: A YAML parser and emitter in C++](https://github.com/jbeder/yaml-cpp)


## License
本ソフトは、どなたでも無料でお使いいただけるフリーソフトですが、開発継続の為に以下で寄付を受け付けております。
尚、現在クローズドソースソフトウェアです。

- [Zenn.dev](https://zenn.dev/beck/) で開発サポート
- [Amazon.co.jp](https://www.amazon.co.jp/dp/BT00DHI8G4) にてギフト券受取先 [beckorz+atto@gmail.com] で支援


## Known issues
- Windows 7 以降のスナップ機能で、画面上部にスクラップウィンドウを持っていくと、スクラップウィンドウのサイズが小さくなってしまう。  
  → スクラップウィンドウを何度かダブルクリックして、サイズを変えると元のサイズに戻ります。


## Thanks
- 元作者様
- うっちー


## Author
beck
mail: beckorz+atto@gmail.com

