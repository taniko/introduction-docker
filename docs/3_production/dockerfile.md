- 軽量なイメージを作る
  - 小さければ小さいほどよい
      - 大きいイメージは速度に影響する
      - 基本的にDockerを本番で起動するときはpullから始まる
  - 軽量なベースイメージを選択する
  - Alpine Linuxがオススメ
  - 最低限のパッケージ・ライブラリしかインストールしない
  - レイヤーのキャッシュを意識する
- multi-stage build
- `ADD` は使わない
- cache