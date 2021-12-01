# 音源の読み込みと波形の表示
波形を少し変わった形で。手軽にローカルで表示させてみる。
## サンプル

![波形サンプル](./README-IMG/2021-12-01%2023.19.03.png)

[サンプル音源](https://dova-s.jp/bgm/play2873.html)

## 利用しているもの
- Node.js
- Express

# 使い方
`./public/` に表示させたい音源ファイルを置く

`./public/test.js` で以下の箇所を編集する

```javascript
document.addEventListener('touchstart', drawAudio('./野良猫は宇宙を目指した.mp3'));
```

`$ node index.js`

`$ open -a '/Applications/Google Chrome.app' http://localhost:8080/`

# 波形の表示を参考にしたサイト
https://css-tricks.com/making-an-audio-waveform-visualizer-with-vanilla-javascript/