# 古いサンプルです
- このサンプルは2023年のものであり、SDKの最新版とは合わない点があります。
- 新しいサンプルをご利用ください:
  - [2024年のGISサンプル](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unity-GISSample)

# PLATEAU SDK for Unity Samples
このリポジトリでは、[PLATEAU SDK for Unity](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unity)を利用すると実際にどのようなアプリケーションが作れるかについて知るためのサンプルプロジェクトを公開しています。

[PLATEAU SDK for Unreal](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unreal)向けサンプルプロジェクトは[こちら](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unreal-Samples)です。

## はじめに
PLATEAU公式サイトで[PLATEAU SDK for Unityのチュートリアル](https://www.mlit.go.jp/plateau/learning/tpc17-1/)を公開しています。

SDKの導入方法、機能の説明、サンプルプロジェクトの内容等について解説していますので、初めてSDKやサンプルプロジェクトを触る方はまずはこちらをご覧ください。


## 動作環境
- Unity 2020.3~

## 導入
- [Releaseページ](https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unity-Samples/releases)から最新版を選択します。
- 掲載されているサンプルプロジェクトをダウンロードします。
- zipファイルを展開してUnityからプロジェクトとして開きます。

## GISSample
![](/README_Images/GISSample.png)
PLATEAU SDKでどのような属性情報にアクセスできるかについて知るためのチュートリアルとして、GISサンプルアプリを提供しています。GISサンプルアプリでは、PLATEAUの3D都市モデルのさまざまな属性情報の表示や、属性情報に応じたフィルタリング・色分けができます。GISサンプルアプリは、サンプルプロジェクトに含まれるAssets/GISSample/Scenes/GISSample.unityを開き、Playすることで実行できます（初期化処理に時間がかかることがあります）。

## GameSample
![](/README_Images/GameSample.png)
3D都市モデルの見栄えの調整とインタラクションの作成方法について知るためのチュートリアルとして、ゲームサンプルアプリを提供しています。ゲームサンプルアプリでは、3D都市モデル内で自動車の走行を再現できます。ゲームサンプルアプリは、サンプルプロジェクトに含まれるAssets/GameSample/Scenes/GameSample.unityを開き、Playすることで実行できます。

## gitからの導入
git lfs の導入が必要であることに注意してください。
```
git lfs install
git clone https://github.com/Project-PLATEAU/PLATEAU-SDK-for-Unity-Samples.git
```

## ライセンス
- 本リポジトリはMITライセンスで提供されています。
- ソースコードおよび関連ドキュメントの著作権は国土交通省に帰属します。

## 注意事項
- 本リポジトリの内容は予告なく変更・削除する可能性があります。
- 本リポジトリの利用により生じた損失及び損害等について、国土交通省はいかなる責任も負わないものとします。
