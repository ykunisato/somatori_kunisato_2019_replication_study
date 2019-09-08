## 杣取・国里(2019) アンへドニア(anhedonia)と遅延割引: Lempert & Pizzagalli (2010)の追試の解析コードとデータの共有

杣取・国里(2019)の「アンへドニア(anhedonia)と遅延割引: Lempert & Pizzagalli (2010)の追試」に関する解析コードとデータについては，OSF([https://osf.io/acqb7/](https://osf.io/acqb7/))にて公開しているが，解析環境などの準備などを手間を省いて検証ができるように，Binderを準備しました。

## Binderの使用方法

以下の「launch binder」というボタンをクリックすると，Binderに移動し，解析コードとデータの準備されたRstudio serverが起動します。

※ BinderでのRstudio serverの起動にはある程度時間がかかります。

<!-- badges: start -->
  [![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ykunisato/somatori_kunisato_2019_replication_study/master?urlpath=rstudio)
<!-- badges: end -->

## 解析の再現方法

BinderでRstudio serverが起動したら，"analysis"フォルダ内の"analyze_data.Rmd"を開いてください。RmdはR Markdownファイルになります。(1)Knitボタンをクリックして，一気に解析を行ってHTMLファイルで確認するか，(2)それぞれのチャンクを上から順番に実施するかのどちらかで杣取・国里(2019)の「アンへドニア(anhedonia)と遅延割引: Lempert & Pizzagalli (2010)の追試」の解析を再現できるかと思います。

※なお，最尤推定は計算の負荷が高いので，Binderで実行しないようにしています。もし推定も実施したい場合は，コードとデータをダウンロードした上で，ローカル環境で行ってください。

## DOI

本リポジトリのDigital Object Identifier(DOI)は，以下になります。

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3402512.svg)](https://doi.org/10.5281/zenodo.3402512)

