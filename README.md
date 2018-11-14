# iOSTONE

## Site

- https://qrac.github.io/iostone/

## About

iOS で使いそうな色を Material Design カラーパレット風に生成しました。

## How To Use

### デザインツールで使う場合

- ツールに合わせて `dist/swatches` のスウォッチファイルを使用
- NSColorList 形式のスウォッチは Mac のさまざまなソフトウェアで共有利用が可能

### コーディングで使う場合

- CSS > デモサイトの色コードを直接コピー
- SCSS > `/src/scss/tone/_iostone.scss` を変数ファイルとして include
- Stylus > `/src/stylus/tone/_iostone.styl` を変数ファイルとして include

[npm](https://www.npmjs.com/package/iostone) で `_iostone.scss` や `_iostone.styl` をインストールして使えます。

```bash
$ npm install iostone
```

## Reference

- [The color system - Material Design](https://material.io/design/color/)

## License

- CC0 1.0 Public Domain

## Credit

- Author: [Qrac](https://qrac.jp)
- Organization: [QRANOKO](https://qranoko.jp)
