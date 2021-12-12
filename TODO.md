# チューニング By Cateiru

## 著しいパフォーマンス低下の原因になっていると考えられるもの

- [画像がフォーマット](./public/images)されていない（数MBのものがそのまま配信されている）
- [動画もやばい](./public/movies)
- [SVGもやばい](./public/sprites/font-awesome)
- フォントが頭おかしい
  - [publicのフォント](./public/fonts)
  - [css](./client/src/styles/webfont.css)
- [サウンド](./public/sounds)もやばい。mp3のまま配信されている

- [念の為 2の18乗 回、最下部かどうかを確認する](https://github.com/cateiru/web-speed-hackathon-2021/blob/b6590a1b739b6dff00288cc8fe358f4291fe66ae/client/src/components/foundation/InfiniteScroll/InfiniteScroll.jsx#L18): もう意味がわからんwwwww
