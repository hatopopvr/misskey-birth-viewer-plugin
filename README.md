# misskey-birth-viewer-plugin
フォローしているユーザーで誕生日が近い方の一覧を簡易に表示するMisskeyプラグインです。
[AiScript](https://github.com/syuilo/aiscript/tree/master)によって記述されています。
本プラグインはアイデアベースで試作したもののため、仕様は暫定的です。
本プラグインの対象は現在同一サーバーのフォローしているユーザーのみになります。

## 使い方
ノート投稿部の`プラグイン`ボタン > `[閲覧]直近の誕生日を取得`を選択すると、ダイアログウインドウにて結果が表示されます。

## 導入
1. [`release`](https://github.com/hatopopvr/misskey-birth-viewer-plugin/releases)から`MisskeyBirthViewer.is`をダウンロードします。
2. ダウンロードした内容を全てコピーします。
3. Misskeyの`設定 > プラグインのインストール`のテキストエリアに貼付けます。
4. `インストール`ボタンを押します。

###  カスタムCSSでのダイアログの表示修正
以下は、ダイアログのテキスト表示を左詰めにしてウインドウサイズを変更するカスタムCSSです。
デフォルトではテキストは中心揃えで、ウインドウ最大サイズが小さいため、作者は変更して利用しています。
数値は自環境に合わせて適切に調整してください。
```css
.xa5A4 {
    min-width: 320px;
    max-width: 2000px;  /* original 480px; */
    box-sizing: border-box;
    text-align: left; /* original center; */
}
```

## 作者
[@hatopop_vr@misskey.io](https://misskey.io/@hatopop_vr)