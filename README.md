# 浸水ナビプラグイン

## このプラグインについて

国土地理院によって公開されている「浸水ナビ（[リンク](https://suiboumap.gsi.go.jp/)）」の APIから浸水シミュレーションのデータを読み込み、表示するプラグインです。特定の破堤点からの浸水域を表示したり、経過時間による変化も操作することが可能です。


## 使用方法

- プラグインをインストールし有効化すると、マップ上に「検索可能範囲」が表示されます。
- プラグイン内の「①降雨規模の選択」からシミュレーションの想定規模を選択します。「検索可能範囲を表示」のチェックをはずすと、マップ上にある検索可能範囲を非表示にできます。
- 「②地点を選択」のマップアイコンをクリックした状態で、検索可能範囲上のシミュレーションをみたい地点をダブルクリックすると、その地点の座標値の取得がされます。
- 「③破堤点の選択」から「破堤点の取得」をクリックすると、浸水シミュレーションが確認できる破堤点の候補が読み込まれます。
  - ※この読み込みには地点によって数十秒〜数分かかる場合があります。
- 「③破堤点の選択」から読み込まれた破堤点から確認したいものを選択し、「浸水シミュレーション実行」をクリックすると、その破堤点が破堤した場合の浸水シミュレーション（初期表示は破堤から10分後）が表示されます。

    ![](https://eukarya-inc.github.io/reearth-plugin-shinsuiNavi/src/img1.png)

  - プラグインに表示されるタイムバーを手動で変更することで、任意の時間経過における浸水シミュレーションを表示することができます。

    ![Untitled](https://eukarya-inc.github.io/reearth-plugin-shinsuiNavi/src/img2.png)

  - プラグインの最下部にある「検索のクリア」をクリックすると、表示されてたシミュレーションをクリアすることができます。
