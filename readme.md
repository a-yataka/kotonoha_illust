# イラスト保存用リポジトリ
イラストの保存とgituhub pagesで動く程度のwebフロント
## ディレクトリ構成
### illust
- kotonoha
    - aoi
        - default
    - akane
        - default
    - pair
        - yuri
        - normal
### docs
- github pagesで公開するディレクトリ
- vue_gallery側で生成されたファイルを置く

### vue_gallery
- vueプロジェクト


# メモ
## ローカル環境
### node,npm,vuecliのバージョンについて
- nodeバージョンはnvmで管理している
- npmはnvmでnodeを入れたときに勝手に入ってきた
- vuecliはnodeを入れたタイミングでグローバルインストールした
- nodeバージョンを変えたとき、vuecliの挙動はどうなってしまうのか。面倒だし怖くてやってない
    - 当面はnode 18.14.0, vue/cli 5.0.8, npm 9.3.1 で維持