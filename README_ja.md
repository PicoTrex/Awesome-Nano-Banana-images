<div align="center">

<img src="images/logo.jpg"  alt="输入图片"> 

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE) 
[![简体中文](https://img.shields.io/badge/简体中文-クリックして表示-orange)](README.md)
[![English](https://img.shields.io/badge/English-クリックして表示-yellow)](README_en.md)
[![日本語](https://img.shields.io/badge/日本語-クリックして表示-green)](README_ja.md)
[![Korean](https://img.shields.io/badge/한국어-눌러서_보기-blue)](README_kr.md)
[![Turkish](https://img.shields.io/badge/Türkçe-Görüntülemek_için_Tıklayın-red)](README_tr.md)
[![Brazilian Portuguese](https://img.shields.io/badge/Português_Brasileiro-Clique_Para_Visualizar-green)](README_ptbr.md)

</div>

> [!NOTE]
> 私たちは Nano-consistent-150k を提案します。これは Nano-Banana を用いて構築された、15万件を超える高品質サンプルから成る初のデータセットであり、多様かつ複雑な編集シナリオにおいて人物アイデンティティの一貫性を維持するよう独自に設計されています。大きな特徴は、その卓越したアイデンティティ一貫性です。単一のポートレートに対し、さまざまなタスクと指示にわたり 35 以上の異なる編集出力を提供します。一貫した人物をアンカーとすることで、同一個人を中心に複数の編集タスク・指示・モダリティをシームレスに結び付けるインタリーブド（interleaved）データの構築が可能になります。
<a href='https://picotrex.github.io/Awesome-Nano-Banana-images/'><img src='https://img.shields.io/badge/🌐 Website-Blog-orange' height="25"></a>
<a href='https://huggingface.co/datasets/Yejy53/Nano-consistent-150k'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Dataset-yellow' height="25"></a>

## 🍌 はじめに

Nano-bananaの厳選画像ギャラリーへようこそ！🤗 

**私たちは、Nano-bananaが様々なタスクシナリオで生成した素晴らしい画像とプロンプトを収集しました**。Googleが持つ画像生成と編集の無限の可能性を総合的に紹介します。このリポジトリが、あなたがNano-bananaをより深く理解する一助となれば幸いです。さあ、一緒にNano-bananaの複数画像融合と創造的な編集能力を解き放ちましょう！✨

これらの事例は、主にTwitter/X 🐦、小紅書(RED) 📕などのソーシャルメディアプラットフォームから収集したものです。

気に入ったら、ぜひ ⭐ Star をクリックしてブックマークしてください！

## 📰 ニュース

- **2025年9月18日：** **Nano-consistent-150k** データセットを公開しました
- **2025年9月9日:** 4️⃣ 4回目のリポジトリ更新
- **2025年9月9日:** 3️⃣ 3回目のリポジトリ更新
- **2025年9月3日:** 2️⃣ 2回目のリポジトリ更新
- **2025年8月28日:** 🎉 1️⃣ ${\color{red} Awesome-Nano-Banana-images 初回更新！}$

## 📑 目次

- [🍌 はじめに](#-はじめに)
- [📰 ニュース](#-ニュース)
- [📑 目次](#-目次)
- [🖼️ 事例](#️-事例)
  - [例 1: イラストからフィギュアへ（by @ZHO\_ZHO\_ZHO）](#例-1-イラストからフィギュアへby-zho_zho_zho)
  - [例 2: 地図の矢印から地上視点の画像を生成（by @tokumin）](#例-2-地図の矢印から地上視点の画像を生成by-tokumin)
  - [例 3: 現実世界をARで情報化（by @bilawalsidhu）](#例-3-現実世界をarで情報化by-bilawalsidhu)
  - [例 4: 3D建物の抽出/アイソメトリックモデルの作成（by @Zieeett）](#例-4-3d建物の抽出アイソメトリックモデルの作成by-zieeett)
  - [例 5: 様々な時代の自分の写真（by @AmirMushich）](#例-5-様々な時代の自分の写真by-amirmushich)
  - [例 6: 複数参照画像からの生成（by @MrDavids1）](#例-6-複数参照画像からの生成by-mrdavids1)
  - [例 7: 写真の自動補正（by @op7418）](#例-7-写真の自動補正by-op7418)
  - [例 8: 手描きイラストで複数キャラクターのポーズを制御（by @op7418）](#例-8-手描きイラストで複数キャラクターのポーズを制御by-op7418)
  - [例 9: 視点を変えた画像の生成（by @op7418）](#例-9-視点を変えた画像の生成by-op7418)
  - [例 10: カスタムキャラクターステッカー（by @op7418）](#例-10-カスタムキャラクターステッカーby-op7418)
  - [例 11: アニメからリアルなコスプレイヤーへ（by @ZHO\_ZHO\_ZHO）](#例-11-アニメからリアルなコスプレイヤーへby-zho_zho_zho)
  - [例 12: キャラクター設定の生成（by @ZHO\_ZHO\_ZHO）](#例-12-キャラクター設定の生成by-zho_zho_zho)
  - [例 13: カラーパレットを使った線画の着色（by @ZHO\_ZHO\_ZHO）](#例-13-カラーパレットを使った線画の着色by-zho_zho_zho)
  - [例 14: 記事のインフォグラフィック（by @黄建同学）](#例-14-記事のインフォグラフィックby-黄建同学)
  - [例 15: 様々な髪型への変更（by @balconychy）](#例-15-様々な髪型への変更by-balconychy)
  - [例 16: モデルの注釈付き解説図（by @berryxia\_ai）](#例-16-モデルの注釈付き解説図by-berryxia_ai)
  - [例 17: カスタム大理石彫刻（by @umesh\_ai）](#例-17-カスタム大理石彫刻by-umesh_ai)
  - [例 18: 食材から料理を生成（by @Gdgtify）](#例-18-食材から料理を生成by-gdgtify)
  - [例 19: 数学問題の解答（by @Gorden Sun）](#例-19-数学問題の解答by-gorden-sun)
  - [例 20: 古い写真のカラー化（by @GeminiApp）](#例-20-古い写真のカラー化by-geminiapp)
  - [例 21: OOTD（今日のコーデ）（by @302.AI）](#例-21-ootd今日のコーデby-302ai)
  - [例 22: キャラクターの着せ替え（by @skirano）](#例-22-キャラクターの着せ替えby-skirano)
  - [例 23: マルチビュー画像の生成（by @Error\_HTTP\_404）](#例-23-マルチビュー画像の生成by-error_http_404)
  - [例 24: 映画の絵コンテ（by @GeminiApp）](#例-24-映画の絵コンテby-geminiapp)
  - [例 25: キャラクターのポーズ修正（by @arrakis\_ai）](#例-25-キャラクターのポーズ修正by-arrakis_ai)
  - [例 26: 線画から画像を生成（by @ZHO\_ZHO\_ZHO）](#例-26-線画から画像を生成by-zho_zho_zho)
  - [例 27: 画像へのウォーターマーク追加（by @AiMachete）](#例-27-画像へのウォーターマーク追加by-aimachete)
  - [例 28: 知識に基づいた画像生成（by @icreatelife）](#例-28-知識に基づいた画像生成by-icreatelife)
  - [例 29: 赤ペンでの注釈（by @AiMachete）](#例-29-赤ペンでの注釈by-aimachete)
  - [例 30: 爆発する食べ物（by @icreatelife）](#例-30-爆発する食べ物by-icreatelife)
  - [例 31: 漫画の作成（by @icreatelife）](#例-31-漫画の作成by-icreatelife)
  - [例 32: アクションフィギュア（by @icreatelife）](#例-32-アクションフィギュアby-icreatelife)
  - [例 33: 地図からアイソメトリックな建物を生成（by @demishassabis）](#例-33-地図からアイソメトリックな建物を生成by-demishassabis)
  - [例 34: 参照画像でキャラクターの表情を制御（by @ZHO\_ZHO\_ZHO）](#例-34-参照画像でキャラクターの表情を制御by-zho_zho_zho)
  - [例 35: イラストの制作過程4コマ（by @ZHO\_ZHO\_ZHO）](#例-35-イラストの制作過程4コマby-zho_zho_zho)
  - [例 36: バーチャルメイク（by @ZHO\_ZHO\_ZHO）](#例-36-バーチャルメイクby-zho_zho_zho)
  - [例 37: メイクの分析（by @ZHO\_ZHO\_ZHO）](#例-37-メイクの分析by-zho_zho_zho)
  - [例 38: Googleマップ視点の中つ国（by @TechHallo）](#例-38-googleマップ視点の中つ国by-techhallo)
  - [例 39: タイポグラフィイラストの生成（by @Umesh）](#例-39-タイポグラフィイラストの生成by-umesh)
  - [例 40: 大量のキャラクターポーズ生成（by @tapehead\_Lab）](#例-40-大量のキャラクターポーズ生成by-tapehead_lab)
  - [例 41: 商品パッケージの生成（by @ZHO\_ZHO\_ZHO）](#例-41-商品パッケージの生成by-zho_zho_zho)
  - [例 42: フィルター/テクスチャの重ね合わせ（by @ZHO\_ZHO\_ZHO）](#例-42-フィルターテクスチャの重ね合わせby-zho_zho_zho)
  - [例 43: キャラクターの輪郭を制御（by @ZHO\_ZHO\_ZHO）](#例-43-キャラクターの輪郭を制御by-zho_zho_zho)
  - [例 44: ライティングの制御（by @ZHO\_ZHO\_ZHO）](#例-44-ライティングの制御by-zho_zho_zho)
  - [例 45: レゴのミニフィギュア（by @ZHO\_ZHO\_ZHO）](#例-45-レゴのミニフィギュアby-zho_zho_zho)
  - [例 46: ガンダムのプラモデル風フィギュア（by @ZHO\_ZHO\_ZHO）](#例-46-ガンダムのプラモデル風フィギュアby-zho_zho_zho)
  - [例 47: ハードウェアの分解図（by @AIimagined）](#例-47-ハードウェアの分解図by-aiimagined)
  - [例 48: 食べ物のカロリー表示（by @icreatelife）](#例-48-食べ物のカロリー表示by-icreatelife)
  - [例 49: 被写体を抽出して透過背景に配置（by @nglprz）](#例-49-被写体を抽出して透過背景に配置by-nglprz)
  - [例 50: 画像の外部拡張と修復（by @bwabbage）](#例-50-画像の外部拡張と修復by-bwabbage)
  - [例 51: 古地図から昔の風景写真を生成（by @levelsio）](#例-51-古地図から昔の風景写真を生成by-levelsio)
  - [例 52: ファッションのコラージュ作成（by @tetumemo）](#例-52-ファッションのコラージュ作成by-tetumemo)
  - [例 53: 精巧で可愛い製品写真（by @azed\_ai）](#例-53-精巧で可愛い製品写真by-azed_ai)
  - [例 54: アニメの像を現実世界に配置（by @riddi0908）](#例-54-アニメの像を現実世界に配置by-riddi0908)
  - [例 55: 痛車の作成（by @riddi0908）](#例-55-痛車の作成by-riddi0908)
  - [例 56: 漫画の構図（by @namaedousiyoka）](#例-56-漫画の構図by-namaedousiyoka)
  - [例 57: 漫画風スタイルへの変換（by @nobisiro\_2023）](#例-57-漫画風スタイルへの変換by-nobisiro_2023)
  - [例 58: アイソメトリックなホログラム図（by @tetumemo）](#例-58-アイソメトリックなホログラム図by-tetumemo)
  - [例 59: マインクラフト風の風景生成（by @tetumemo）](#例-59-マインクラフト風の風景生成by-tetumemo)
  - [例 60: マテリアル球の質感を適用（by @ZHO\_ZHO\_ZHO）](#例-60-マテリアル球の質感を適用by-zho_zho_zho)
  - [例 61: 間取り図の3Dレンダリング（by @op7418）](#例-61-間取り図の3dレンダリングby-op7418)
  - [例 62: カメラパラメータの再設定（by @hckinz）](#例-62-カメラパラメータの再設定by-hckinz)
  - [例 63: 証明写真の作成（by @songguoxiansen）](#例-63-証明写真の作成by-songguoxiansen)
  - [例 64: A6サイズの飛び出すカード（by @Gdgtify）](#例-64-a6サイズの飛び出すカードby-gdgtify)
  - [例 65: チェスセットのデザイン（by @Gdgtify）](#例-65-チェスセットのデザインby-gdgtify)
  - [例 66: 時代を比較する分割写真（by @fofrAI）](#例-66-時代を比較する分割写真by-fofrai)
  - [例 67: ジュエリーコレクションのデザイン（by @Gdgtify）](#例-67-ジュエリーコレクションのデザインby-gdgtify)
  - [例 68: グッズデザイン（by @0xFramer）](#例-68-グッズデザインby-0xframer)
  - [例69：モデルホログラム投影（by @UNIBRACITY）](#例69モデルホログラム投影by-unibracity)
  - [例70：巨大人物の足場（by @songguoxiansen）](#例70巨大人物の足場by-songguoxiansen)
  - [例71：リモートセンシング画像の建物抽出（by @lehua555）](#例71リモートセンシング画像の建物抽出by-lehua555)
  - [例72：部品抽出（by @tetumemo）](#例72部品抽出by-tetumemo)
  - [例73：ハンバーガーの具材を取り除く（by @bind\_lux、本ケース提供：@jeanlucaslima）](#例73ハンバーガーの具材を取り除くby-bind_lux本ケース提供jeanlucaslima)
  - [例74：画像の高解像度修復（by @op7418）](#例74画像の高解像度修復by-op7418)
  - [例75：画像からミニチュアシーン生成（by @techhalla）](#例75画像からミニチュアシーン生成by-techhalla)
  - [例76：科学普及マンガ（by @op7418）](#例76科学普及マンガby-op7418)
  - [例77：カスタムキャラクターのスタンプ生成（by @vista8）](#例77カスタムキャラクターのスタンプ生成by-vista8)
  - [例78：食べかけの食べ物を復元（by @googlejapan）](#例78食べかけの食べ物を復元by-googlejapan)
  - [例79：格闘ゲームのインターフェース制作（by @NanoBanana\_labs）](#例79格闘ゲームのインターフェース制作by-nanobanana_labs)
  - [例80：モデルの断面図（by @old\_pgmrs\_will）](#例80モデルの断面図by-old_pgmrs_will)
  - [例81：海賊の手配書（by @AI\_Kei75）](#例81海賊の手配書by-ai_kei75)
  - [例82：周辺展示棚（by @tokyo\_Valentine）](#例82周辺展示棚by-tokyo_valentine)
  - [例83：漫画展示ブース（by @tokyo\_Valentine）](#例83漫画展示ブースby-tokyo_valentine)
  - [例84：線画から落書き風イラストへ変換（by @hAru\_mAki\_ch）](#例84線画から落書き風イラストへ変換by-haru_maki_ch)
  - [例85：現代美術展示空間（by @UNIBRACITY）](#例85現代美術展示空間by-unibracity)
  - [例86：ダークゴシックタロットカード（by @ImperfectEngel）](#例86ダークゴシックタロットカードby-imperfectengel)
  - [例88：ガラス瓶の記念品（by @NanoBanana\_labs）](#例88ガラス瓶の記念品by-nanobanana_labs)
  - [例89：ミニチュアショップ（by @NanoBanana\_labs）](#例89ミニチュアショップby-nanobanana_labs)
  - [例90：Vtuberになる（by @AI\_Kei75）](#例90vtuberになるby-ai_kei75)
  - [例91：駅の映画ポスター（by @AI\_Kei75）](#例91駅の映画ポスターby-ai_kei75)
- [🙏 謝辞](#-謝辞)

## 🖼️ 事例

<!-- 例 1: イラストからフィギュアへ（by @ZHO_ZHO_ZHO） -->
### 例 1: [イラストからフィギュアへ](https://x.com/ZHO_ZHO_ZHO/status/1958539464994959715)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case1/input0.jpg" width="200" alt="入力画像"> | <img src="images/case1/output0.jpg" width="200" alt="出力結果"> |

**入力:** フィギュア化したいキャラクターの参照画像をアップロードします。

**プロンプト:**

```
この写真をキャラクターフィギュアにしてください。背景にはキャラクターの画像が印刷された箱を置き、その画面にはBlenderのモデリング過程が表示されているコンピューターを配置してください。箱の前には、キャラクターフィギュアが立つ円形のプラスチック製台座を追加してください。可能であれば、シーンを屋内に設定してください。
```

<!-- 例 2: 地図の矢印から地上視点の画像を生成（by @tokumin） -->
### 例 2: [地図の矢印から地上視点の画像を生成](https://x.com/tokumin/status/**1960583251460022626**)（by [@tokumin](https://x.com/tokumin)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case2/input.jpg" width="300" alt="入力画像"> | <img src="images/case2/output.jpg" width="300" alt="出力結果"> |
| <img src="images/case2/input3.jpg" width="300" alt="入力画像"> | <img src="images/case2/output3.jpg" width="300" alt="出力結果"> |
| <img src="images/case2/input2.jpg" width="300" alt="入力画像"> | <img src="images/case2/output2.jpg" width="300" alt="出力結果"> |

**入力:** 赤い矢印が含まれるGoogleマップの画像をアップロードします。

**プロンプト:**

```
赤い矢印が見ているものを描いてください
/
赤い円から矢印の方向に見た現実世界の視点を描いてください
```

<!-- 例 3: 現実世界をARで情報化（by @bilawalsidhu） -->
### 例 3: [現実世界をARで情報化](https://x.com/bilawalsidhu/status/1960529167742853378)（by [@bilawalsidhu](https://x.com/bilawalsidhu)）

| 出力 |
|:---:|
| <img src="images/case3/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
あなたは位置情報ベースのAR体験ジェネレーターです。この画像内の[興味のある地点]をハイライトし、それに関する情報を注釈で付けてください。
```

> [!NOTE]
> **プロンプト内の`[興味のある地点]`に、注釈を付けたい場所の名前を入力してください。**

<!-- 例 4: 3D建物の抽出/アイソメトリックモデルの作成（by @Zieeett） -->
### 例 4: [3D建物の抽出/アイソメトリックモデルの作成](https://x.com/Zieeett/status/1960420874806247762)（by [@Zieeett](https://x.com/Zieeett)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case4/input.jpg" width="300" alt="入力画像"> | <img src="images/case4/output.jpg" width="300" alt="出力結果"> |
| <img src="images/case4/input2.jpg" width="300" alt="入力画像"> | <img src="images/case4/output2.jpg" width="300" alt="出力結果"> |

**入力:** 対象物を含む画像をアップロードします。

**プロンプト:**

```
画像を昼間のアイソメトリックビューにしてください[建物のみ]
```

> [!NOTE]
> **必要に応じて`[角括弧]`内の情報を変更してください（例：乗り物、人物など）。**

<!-- 例 5: 様々な時代の自分の写真（by @AmirMushich） -->
### 例 5: [様々な時代の自分の写真](https://x.com/AmirMushich/status/1960810850224091439)（by [@AmirMushich](https://x.com/AmirMushich)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case5/input.jpg" width="300" alt="入力画像"> | <img src="images/case5/output.jpg" width="300" alt="出力結果"> |

**入力:** 人物の写真をアップロードします。

**プロンプト:**

```
キャラクターのスタイルを[1970]年代のクラシックな[男性]スタイルに変更してください。

[長いカーリーヘア]と
[長い口ひげ]を追加し、
背景を象徴的な[カリフォルニアの夏の風景]に変更してください。

キャラクターの顔は変更しないでください。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、あなたの希望する時代や詳細情報に変更してください。**

<!-- 例 6: 複数参照画像からの生成（by @MrDavids1） -->
### 例 6: [複数参照画像からの生成](https://x.com/MrDavids1/status/1960783672665128970)（by [@MrDavids1](https://x.com/MrDavids1)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case6/input.jpg" width="300" alt="入力画像"> | <img src="images/case6/output.jpg" width="300" alt="出力結果"> |

**入力:** 複数の参照画像をアップロードします。

**プロンプト:**

```
モデルがピンクのBMWに寄りかかってポーズをとっています。彼女は以下のアイテムを身につけており、背景は薄いグレーです。緑色のエイリアンはキーチェーンで、ピンクのハンドバッグに取り付けられています。モデルの肩にはピンクのオウムもいます。隣にはピンクの首輪とゴールドのヘッドフォンをつけたパグが座っています。
```

> [!NOTE]
> **プロンプトには、複数の参照オブジェクトを含む詳細な説明が必要です。**

<!-- 例 7: 写真の自動補正（by @op7418） -->
### 例 7: [写真の自動補正](https://x.com/op7418/status/1960528616573558864)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case7/input.jpg" width="300" alt="入力画像"> | <img src="images/case7/output.jpg" width="300" alt="出力結果"> |

**入力:** 修正したい画像をアップロードします。

**プロンプト:**

```
この写真は退屈で平凡です。もっと良くしてください！コントラストを上げ、色を鮮やかにし、光を改善して豊かにしてください。構図に影響するディテールはトリミングや削除しても構いません。
```

<!-- 例 8: 手描きイラストで複数キャラクターのポーズを制御（by @op7418） -->
### 例 8: [手描きイラストで複数キャラクターのポーズを制御](https://x.com/op7418/status/1960536717242573181)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case8/input.jpg" width="300" alt="入力画像"> | <img src="images/case8/output.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの画像と手描きのスケッチをアップロードします。

**プロンプト:**

```
この2人のキャラクターを、図3のポーズで戦わせてください。適切な視覚的背景とシーンのインタラクションを追加し、生成画像の比率を16:9にしてください。
```

<!-- 例 9: 視点を変えた画像の生成（by @op7418） -->
### 例 9: [視点を変えた画像の生成](https://x.com/op7418/status/1960896630586310656)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case9/input.jpg" width="300" alt="入力画像"> | <img src="images/case9/output.jpg" width="300" alt="出力結果"> |

**入力:** 地上から撮影した写真をアップロードします。

**プロンプト:**

```
この写真を真上からの視点に変換し、撮影者の位置をマークしてください。
```

<!-- 例 10: カスタムキャラクターステッカー（by @op7418） -->
### 例 10: [カスタムキャラクターステッカー](https://x.com/op7418/status/1960385812132192509)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case10/input.jpg" width="300" alt="入力画像"> | <img src="images/case10/output.jpg" width="300" alt="出力結果"> |

**入力:** ステッカーの参照画像とキャラクターの画像をアップロードします。

**プロンプト:**

```
このキャラクターを、図2のような白い輪郭のステッカーにしてください。キャラクターはウェブイラスト風に変換し、図1を説明する遊び心のある白い輪郭の短いフレーズを追加してください。
```

<!-- 例 11: アニメからリアルなコスプレイヤーへ（by @ZHO_ZHO_ZHO） -->
### 例 11: [アニメからリアルなコスプレイヤーへ](https://x.com/ZHO_ZHO_ZHO/status/1960946893971706306)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case11/input.jpg" width="300" alt="入力画像"> | <img src="images/case11/output.jpg" width="300" alt="出力結果"> |

**入力:** イラスト画像をアップロードします。

**プロンプト:**

```
このイラストのコスプレをしている女の子の写真を生成してください。背景はコミケに設定してください。
```

<!-- 例 12: キャラクター設定の生成（by @ZHO_ZHO_ZHO） -->
### 例 12: [キャラクター設定の生成](https://x.com/ZHO_ZHO_ZHO/status/1960669234276753542)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case12/input.jpg" width="300" alt="入力画像"> | <img src="images/case12/output.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像をアップロードします。

**プロンプト:**

```
このキャラクターのデザイン設定を生成してください（キャラクターデザイン）

プロポーション設定（身長比較、頭身比など）
三面図（正面、側面、背面）
表情設定（表情シート）
ポーズ設定（ポーズシート）→ 様々な一般的なポーズ
衣装設定（コスチュームデザイン）
```

<!-- 例 13: カラーパレットを使った線画の着色（by @ZHO_ZHO_ZHO） -->
### 例 13: [カラーパレットを使った線画の着色](https://x.com/ZHO_ZHO_ZHO/status/1960652077891510752)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case13/input.jpg" width="300" alt="入力画像"> | <img src="images/case13/output.jpg" width="300" alt="出力結果"> |

**入力:** 線画とカラーパレットの画像をアップロードします。

**プロンプト:**

```
図2のカラーパレットを正確に使って、図1のキャラクターに着色してください。
```

<!-- 例 14: 記事のインフォグラフィック（by @黄建同学） -->
### 例 14: [記事のインフォグラフィック](https://weibo.com/5648162302/5204549851155423?wm=3333_2001&from=10F8393010&sourcetype=weixin&s_trans=7836809604_5204549851155423&s_channel=4)（by [@黄建同学](https://weibo.com/u/5648162302)）

| 出力 |
|:---:|
| <img src="images/case14/output.jpg" width="300" alt="出力結果"> |

**入力:** ブログ記事や文章をアップロードします。

**プロンプト:**

```
記事の内容からインフォグラフィックを生成してください。
要件：
1. 内容を英語に翻訳し、記事の重要な情報を抽出する
2. 図の内容は簡潔にし、大見出しのみを残す
3. 図中のテキストは英語を使用する
4. 可愛らしいキャラクターや要素を豊富に追加する
```

<!-- 例 15: 様々な髪型への変更（by @balconychy） -->
### 例 15: [様々な髪型への変更](https://x.com/balconychy/status/1960665038504779923)（by [@balconychy](https://x.com/balconychy)）

| 出力 |
|:---:|
| <img src="images/case15/output.jpg" width="300" alt="出力結果"> |

**入力:** 髪型を変えたい人物の画像をアップロードします。

**プロンプト:**

```
この人物の様々な髪型のアバターを九分割（3x3グリッド）で生成してください。
```

<!-- 例 16: モデルの注釈付き解説図（by @berryxia_ai） -->
### 例 16: [モデルの注釈付き解説図](https://x.com/berryxia_ai/status/1960708465586004305)（by [@berryxia_ai](https://x.com/berryxia_ai)）

| 出力 |
|:---:|
| <img src="images/case16/output.jpg" width="300" alt="出力結果"> |

> [!CAUTION]
> アノテーション結果には多くの誤りが含まれています ⚠️ Nano-Banana のアノテーション結果は完全に正確ではないため、ご利用の際には必ず情報の正確性を確認してください

**プロンプト:**

```
学術発表用に[3D人体器官モデルの表示例：心臓]を描き、その原理と[各器官]の機能を説明するための注釈を付けてください。非常にリアルで、忠実に再現され、非常に精細なデザインにしてください。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、表示したいモデルの名前に変更してください。**

<!-- 例 17: カスタム大理石彫刻（by @umesh_ai） -->
### 例 17: [カスタム大理石彫刻](https://x.com/umesh_ai/status/1960370946562564353)（by [@umesh_ai](https://x.com/umesh_ai)）

| 出力 |
|:---:|
| <img src="images/case17/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
画像に写っている被写体を、輝く大理石で作られた超詳細な彫刻の写実的な画像にしてください。彫刻は滑らかで反射する大理石の表面を持ち、その光沢と芸術的な技巧を強調してください。デザインはエレガントで、大理石の美しさと深みを際立たせてください。画像内の照明は彫刻の輪郭と質感を高め、視覚的に見事で魅力的な効果を生み出してください。
```

<!-- 例 18: 食材から料理を生成（by @Gdgtify） -->
### 例 18: [食材から料理を生成](https://x.com/Gdgtify/status/1960907695348691075)（by [@Gdgtify](https://x.com/Gdgtify)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case18/input1.jpg" width="300" alt="入力画像"> | <img src="images/case18/output1.jpg" width="300" alt="出力結果"> |
| <img src="images/case18/input2.jpg" width="300" alt="入力画像"> | <img src="images/case18/output2.jpg" width="300" alt="出力結果"> |
| <img src="images/case18/input3.jpg" width="300" alt="入力画像"> | <img src="images/case18/output3.jpg" width="300" alt="出力結果"> |

**入力:** 様々な食材が写った写真をアップロードします。

**プロンプト:**

```
これらの食材で美味しいランチを作って、お皿に盛り付けてください。お皿のクローズアップビューで、他の皿や食材は取り除いてください。
```

<!-- 例 19: 数学問題の解答（by @Gorden Sun） -->
### 例 19: [数学問題の解答](https://www.xiaohongshu.com/explore/68ade0e7000000001d036677?note_flow_source=wechat&xsec_token=AB4tWI6xCrE2v5euckYXKCBlbQbA-YNoqI5iKKqqQwWpY=)（by [@Gorden Sun](https://www.xiaohongshu.com/user/profile/632e72f900000000230397fe?xsec_token=ABeSWJqqsTwTtj3KG1HSTt_vwRcODR4jDJnj2dp0k42YI%3D&xsec_source=pc_note)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case19/input.jpg" width="300" alt="入力画像"> | <img src="images/case19/output.jpg" width="300" alt="出力結果"> |

**入力:** 数学の問題をアップロードします。

**プロンプト:**

```
問題に基づいて、対応する場所に問題の答えを書き込んでください。
```

<!-- 例 20: 古い写真のカラー化（by @GeminiApp） -->
### 例 20: [古い写真のカラー化](https://x.com/GeminiApp/status/1960347483021959197)（by [@GeminiApp](https://x.com/GeminiApp)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case20/input.jpg" width="300" alt="入力画像"> | <img src="images/case20/output.jpg" width="300" alt="出力結果"> |

**入力:** 修復が必要な古い写真をアップロードします。

**プロンプト:**

```
この写真を修復してカラー化してください。
```

<!-- 例 21: OOTD（今日のコーデ）（by @302.AI） -->
### 例 21: [OOTD（今日のコーデ）](https://medium.com/%40302.AI/google-nano-banana-vs-qwen-gpt-flux-topping-the-image-editing-leaderboard-96038b01bdcd)（by [@302.AI](https://medium.com/@302.AI)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case21/input.jpg" width="300" alt="入力画像"> | <img src="images/case21/output.jpg" width="300" alt="出力結果"> |

**入力:** 人物の画像と服装の画像をアップロードします。

**プロンプト:**

```
画像1の人物を選び、画像2のすべての服とアクセサリーを着せてください。屋外で、自然光を使い、スタイリッシュなストリートスタイルで、鮮明な全身ショットの一連のリアルなOOTD風写真を撮影してください。画像1の人物のアイデンティティとポーズは維持しつつ、画像2の完全な服装とアクセサリーを、まとまりのあるスタイリッシュな方法で見せてください。
```

<!-- 例 22: キャラクターの着せ替え（by @skirano） -->
### 例 22: [キャラクターの着せ替え](https://x.com/skirano/status/1960343968320737397)（by [@skirano](https://x.com/skirano)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case22/input.jpg" width="300" alt="入力画像"> | <img src="images/case22/output.jpg" width="300" alt="出力結果"> |

**入力:** 人物の画像と服の画像をアップロードします。

**プロンプト:**

```
入力画像の人物の服装を、参照画像に示されている対象の服装に置き換えてください。人物のポーズ、表情、背景、全体のリアリティは変更しないでください。新しい服装が自然に見え、体にフィットし、光と影と一致するようにしてください。人物のアイデンティティや環境は変更せず、服だけを変えてください。
```

<!-- 例 23: マルチビュー画像の生成（by @Error_HTTP_404） -->
### 例 23: [マルチビュー画像の生成](https://x.com/Error_HTTP_404/status/1960405116701303294)（by [@Error_HTTP_404](https://x.com/Error_HTTP_404)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case23/input.jpg" width="300" alt="入力画像"> | <img src="images/case23/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
正面、背面、左、右、上、下のビューを白い背景で生成してください。均等に配置し、被写体は一貫させてください。アイソメトリック投影でお願いします。
```

<!-- 例 24: 映画の絵コンテ（by @GeminiApp） -->
### 例 24: [映画の絵コンテ](https://x.com/GeminiApp)（by [@GeminiApp](https://x.com/GeminiApp)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case24/input.jpg" width="300" alt="入力画像"> | <img src="images/case24/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
この2人のキャラクターを使って、クラシックな白黒フィルム・ノワールの探偵物語を、12枚の画像で構成される魅力的な12部構成のストーリーを作成してください。物語は、彼らが失われた宝物の手がかりを探し、最終的に発見するという内容にしてください。物語全体はスリリングで、感情的な高低があり、素晴らしいどんでん返しとクライマックスで終わるようにしてください。画像には一切の文字やテキストを含めず、純粋に画像だけで物語を語ってください。
```

<!-- 例 25: キャラクターのポーズ修正（by @arrakis_ai） -->
### 例 25: [キャラクターのポーズ修正](https://x.com/arrakis_ai/status/1955901155726516652)（by [@arrakis_ai](https://x.com/arrakis_ai)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case25/input.jpg" width="300" alt="入力画像"> | <img src="images/case25/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
写真の中の人をまっすぐ正面を向かせてください。
```

<!-- 例 26: 線画から画像を生成（by @ZHO_ZHO_ZHO） -->
### 例 26: [線画から画像を生成](https://x.com/ZHO_ZHO_ZHO/status/1961024423596872184)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case26/input.jpg" width="300" alt="入力画像"> | <img src="images/case26/output.jpg" width="300" alt="出力結果"> |

**入力:** 線画と参照画像をアップロードします。

**プロンプト:**

```
図1の人物を図2のポーズに変更し、プロのスタジオで撮影してください。
```

<!-- 例 27: 画像へのウォーターマーク追加（by @AiMachete） -->
### 例 27: [画像へのウォーターマーク追加](https://x.com/AiMachete/status/1963038793705128219)（by [@AiMachete](https://x.com/AiMachete)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case27/input.jpg" width="300" alt="入力画像"> | <img src="images/case27/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
画像全体に「TRUMP」という単語をウォーターマークとして繰り返し入れてください。
```

<!-- 例 28: 知識に基づいた画像生成（by @icreatelife） -->
### 例 28: [知識に基づいた画像生成](https://x.com/icreatelife/status/1962998951948517428)（by [@icreatelife](https://x.com/icreatelife)）

| 出力 |
|:---:|
| <img src="images/case28/output.jpg" width="300" alt="出力結果"> |
| <img src="images/case28/output1.jpg" width="300" alt="出力結果"> |

**プロンプト:**

```
世界の最も高いビル5つのインフォグラフィックを作成してください / 地球上で最も甘いものについてのカラフルなインフォグラフィックを作成してください
```

<!-- 例 29: 赤ペンでの注釈（by @AiMachete） -->
### 例 29: [赤ペンでの注釈](https://x.com/AiMachete/status/1962356993550643355)（by [@AiMachete](https://x.com/AiMachete)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case29/input.jpg" width="300" alt="入力画像"> | <img src="images/case29/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
この画像を分析してください。改善できる点を赤ペンで示してください。
```

<!-- 例 30: 爆発する食べ物（by @icreatelife） -->
### 例 30: [爆発する食べ物](https://x.com/icreatelife/status/1962724040205803773)（by [@icreatelife](https://x.com/icreatelife)）

| 出力 |
|:---:|
| <img src="images/case30/output.jpg" width="300" alt="出力結果"> |
| <img src="images/case30/output1.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
この製品をドラマチックでモダンなシーンで撮影してください。新鮮さと栄養価を示すために、新鮮で生の主要な材料が製品の周りを爆発的に外側に向かってダイナミックに飛び散る様子を伴わせてください。プロモーション広告用のショットで、テキストはなし、製品を強調し、主要なブランドカラーを背景にしてください。
```

<!-- 例 31: 漫画の作成（by @icreatelife） -->
### 例 31: [漫画の作成](https://x.com/icreatelife/status/1961977580849873169)（by [@icreatelife](https://x.com/icreatelife)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case31/input.jpg" width="300" alt="入力画像"> | <img src="images/case31/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
アップロードされた画像に基づいて、漫画のコマを作成し、テキストを追加して、魅力的なストーリーを書いてください。ファンタジー漫画をお願いします。
```

<!-- 例 32: アクションフィギュア（by @icreatelife） -->
### 例 32: [アクションフィギュア](https://x.com/icreatelife/status/1961653618529935720)（by [@icreatelife](https://x.com/icreatelife)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case32/input.jpg" width="300" alt="入力画像"> | <img src="images/case32/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
「AI Evangelist - Kris」と書かれたアクションフィギュアを作成し、[コーヒー、亀、ノートパソコン、スマートフォン、ヘッドフォン]を付けてください。
```
> [!NOTE]
> **`[角括弧]`内のテキストを、追加したいアイテムに変更してください。**


<!-- 例 33: 地図からアイソメトリックな建物を生成（by @demishassabis） -->
### 例 33: [地図からアイソメトリックな建物を生成](https://x.com/demishassabis/status/1961077016830083103)（by [@demishassabis](https://x.com/demishassabis)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case33/input.jpg" width="300" alt="入力画像"> | <img src="images/case33/output.jpg" width="300" alt="出力結果"> |

**入力:** 地図の参照画像をアップロードします。

**プロンプト:**

```
この場所のランドマークを、ゲーム「テーマパーク」のスタイルでアイソメトリック画像（建物のみ）にしてください。
```

<!-- 例 34: 参照画像でキャラクターの表情を制御（by @ZHO_ZHO_ZHO） -->
### 例 34: [参照画像でキャラクターの表情を制御](https://x.com/ZHO_ZHO_ZHO/status/1963156830458085674)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case34/case.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像と表情の参照画像をアップロードします。

**プロンプト:**

```
図1の人物を、図2の人物の表情に変えてください。
```

<!-- 例 35: イラストの制作過程4コマ（by @ZHO_ZHO_ZHO） -->
### 例 35: [イラストの制作過程4コマ](https://x.com/ZHO_ZHO_ZHO/status/1961772524611768452)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case35/case.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像をアップロードします。

**プロンプト:**

```
このキャラクターの制作過程を4コマで生成してください。第一段階：線画、第二段階：ベタ塗り、第三段階：影付け、第四段階：仕上げ。テキストは不要です。
```

<!-- 例 36: バーチャルメイク（by @ZHO_ZHO_ZHO） -->
### 例 36: [バーチャルメイク](https://x.com/ZHO_ZHO_ZHO/status/1962778069242126824)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case36/case.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像とメイクの参照画像をアップロードします。

**プロンプト:**

```
図1の人物に、図1のポーズを保ったまま図2のメイクを施してください。
```

<!-- 例 37: メイクの分析（by @ZHO_ZHO_ZHO） -->
### 例 37: [メイクの分析](https://x.com/ZHO_ZHO_ZHO/status/1962784384693739621)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case37/input.jpg" width="300" alt="入力画像"> | <img src="images/case37/output.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像をアップロードします。

**プロンプト:**

```
この画像を分析してください。改善できる点を赤ペンで示してください。
```

<!-- 例 38: Googleマップ視点の中つ国（by @TechHallo） -->
### 例 38: [Googleマップ視点の中つ国](https://x.com/techhalla/status/1962292272227102941)（by [@TechHallo](https://x.com/techhalla)）

| 出力 |
|:---:|
| <img src="images/case38/output.jpg" width="300" alt="出力結果"> |

**プロンプト:**

```
ドライブレコーダーによるGoogleストリートビューショット | [ホビット村の通り] | [庭仕事やパイプを吸うなど日常の仕事をしているホビットたち] | [晴天]
```

> [!NOTE]
> **`[角括弧]`内のテキストを、希望する場所や天候に変更してください。**

<!-- 例 39: タイポグラフィイラストの生成（by @Umesh） -->
### 例 39: [タイポグラフィイラストの生成](https://x.com/umesh_ai/status/1961110485543371145)（by [@Umesh](https://x.com/umesh_ai)）

| 出力 |
|:---:|
| <img src="images/case39/output.jpg" width="300" alt="出力結果"> |

**プロンプト:**

```
「riding a bike」というフレーズの文字だけを使って、自転車に乗るシーンのミニマルな白黒タイポグラフィイラストを作成してください。各文字は、乗り手、自転車、動きの感覚を形成するように創造的に形作られるか配置されるべきです。デザインはクリーンで超ミニマルであり、追加の形や線を使わずに、完全に変更された「riding a bike」の文字で構成されるべきです。文字は、シーンの自然な形を模倣するように流れるかカーブしているべきですが、それでもなお読みやすくしてください。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、希望するテキストに変更してください。**

<!-- 例 40: 大量のキャラクターポーズ生成（by @tapehead_Lab） -->
### 例 40: [大量のキャラクターポーズ生成](https://x.com/tapehead_Lab/status/1960878455299694639)（by [@tapehead_Lab](https://x.com/tapehead_Lab)）

| 例 |
|:---:|
| <img src="images/case40/case.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像をアップロードします。

**プロンプト:**

```
このイラストのポーズ集を作成し、様々なポーズをとらせてください！
```

<!-- 例 41: 商品パッケージの生成（by @ZHO_ZHO_ZHO） -->
### 例 41: [商品パッケージの生成](https://x.com/ZHO_ZHO_ZHO/status/1962763864875167971)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case41/case.jpg" width="300" alt="出力結果"> |

**入力:** 商品の参照画像とパッケージの参照画像をアップロードします。

**プロンプト:**

```
図1のデザインを図2の缶に貼り付け、ミニマルなデザインのセットに配置してください。プロの写真撮影でお願いします。
```

<!-- 例 42: フィルター/テクスチャの重ね合わせ（by @ZHO_ZHO_ZHO） -->
### 例 42: [フィルター/テクスチャの重ね合わせ](https://x.com/ZHO_ZHO_ZHO/status/1962520937011855793)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case42/case.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像とフィルター/テクスチャの参照画像をアップロードします。

**プロンプト:**

```
図1の写真に図2の[ガラス]の効果を重ねてください。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、希望するフィルター/テクスチャに変更してください。**

<!-- 例 43: キャラクターの輪郭を制御（by @ZHO_ZHO_ZHO） -->
### 例 43: [キャラクターの輪郭を制御](https://x.com/ZHO_ZHO_ZHO/status/1961802767493939632)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case43/case.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像と顔の輪郭の参照画像をアップロードします。

**プロンプト:**

```
図1のキャラクターを、図2の顔の輪郭に合わせてデフォルメ（ちびキャラ）化してください。
```

<!-- 例 44: ライティングの制御（by @ZHO_ZHO_ZHO） -->
### 例 44: [ライティングの制御](https://x.com/ZHO_ZHO_ZHO/status/1961779457372602725)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case44/case.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像とライティングの参照画像をアップロードします。

**プロンプト:**

```
図1のキャラクターを、図2のライティングに変更してください。暗い部分が影になります。
```

<!-- 例 45: レゴのミニフィギュア（by @ZHO_ZHO_ZHO） -->
### 例 45: [レゴのミニフィギュア](https://x.com/ZHO_ZHO_ZHO/status/1961395526198595771)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case45/input.jpg" width="300" alt="入力画像"> | <img src="images/case45/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
写真の人物をレゴミニフィギュアのパッケージボックス風に変換し、アイソメトリックビューで表示してください。ボックスには「ZHOGUE」というタイトルを付けてください。ボックスの中には、写真の人物を基にしたレゴミニフィギュアと、その必需品（化粧品、バッグなど）をレゴのアクセサリーとして表示してください。ボックスの横には、パッケージ化されていない実際のレゴミニフィギュア自体も、リアルで鮮やかなスタイルでレンダリングして表示してください。
```

<!-- 例 46: ガンダムのプラモデル風フィギュア（by @ZHO_ZHO_ZHO） -->
### 例 46: [ガンダムのプラモデル風フィギュア](https://x.com/ZHO_ZHO_ZHO/status/1961412823340265509)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case46/input.jpg" width="300" alt="入力画像"> | <img src="images/case46/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
写真の人物をガンダムモデルキットのパッケージボックス風に変換し、アイソメトリックビューで表示してください。ボックスには「ZHOGUE」というタイトルを付けてください。ボックスの中には、写真の人物のガンダム風メカバージョンと、その必需品（化粧品、バッグなど）を未来的なメカアクセサリーとして再デザインしたものを表示してください。パッケージは、技術的なイラスト、取扱説明書風の詳細、SFフォントを含む、実際のガンプラボックスに似せるべきです。ボックスの横には、実際のガンダム風メカフィギュア自体も、公式バンダイのプロモーションレンダーに似た、リアルで生き生きとしたスタイルでパッケージ外にレンダリングして表示してください。
```

<!-- 例 47: ハードウェアの分解図（by @AIimagined） -->
### 例 47: [ハードウェアの分解図](https://x.com/AIimagined/status/1961431851245211958)（by [@AIimagined](https://x.com/AIimagined)）

| 出力 |
|:---:|
| <img src="images/case47/output.jpg" width="300" alt="出力結果"> |

**プロンプト:**

```
デジタル一眼レフカメラの分解図で、レンズ、フィルター、内部コンポーネント、センサー、ネジ、ボタン、ビューファインダー、筐体、回路基板など、すべての付属品と内部コンポーネントを示してください。デジタル一眼レフの赤いアクセントは維持してください。
```

<!-- 例 48: 食べ物のカロリー表示（by @icreatelife） -->
### 例 48: [食べ物のカロリー表示](https://x.com/icreatelife/status/1963646757222715516)（by [@icreatelife](https://x.com/icreatelife)）

| 出力 |
|:---:|
| <img src="images/case48/output.jpg" width="300" alt="出力結果"> |

**入力:** 食べ物の参照画像をアップロードします。

**プロンプト:**

```
この食事に、食べ物の名前、カロリー密度、おおよそのカロリーを注釈で付けてください。
```

<!-- 例 49: 被写体を抽出して透過背景に配置（by @nglprz） -->
### 例 49: [被写体を抽出して透過背景に配置](https://x.com/nglprz/status/1961494974555394068)（by [@nglprz](https://x.com/icreatelife)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case49/input.jpg" width="300" alt="入力画像"> | <img src="images/case49/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
[侍]を抽出して、背景を透過にしてください。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、抽出したいオブジェクトに変更してください。**

<!-- 例 50: 画像の外部拡張と修復（by @bwabbage） -->
### 例 50: [画像の外部拡張と修復](https://x.com/bwabbage/status/1962903212937130450)（by [@bwabbage](https://x.com/bwabbage)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case50/input.jpg" width="300" alt="入力画像"> | <img src="images/case50/output.jpg" width="300" alt="出力結果"> |

**入力:** 市松模様の（透過）領域を含む画像をアップロードします。

**プロンプト:**

```
画像の市松模様（透過）部分を修復し、完全で一貫性のある写真に復元してください。
```

<!-- 例 51: 古地図から昔の風景写真を生成（by @levelsio） -->
### 例 51: [古地図から昔の風景写真を生成](https://x.com/levelsio/status/1961595333034598487)（by [@levelsio](https://x.com/levelsio)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case51/input.jpg" width="300" alt="入力画像"> | <img src="images/case51/output.jpg" width="300" alt="出力結果"> |

**入力:** 歴史的な参照画像をアップロードします。

**プロンプト:**

```
フルカラー写真。1660年のニューアムステルダム。今日撮影された写真のように、完全に現代的な色合いにしてください。
```

<!-- 例 52: ファッションのコラージュ作成（by @tetumemo） -->
### 例 52: [ファッションのコラージュ作成](https://x.com/tetumemo/status/1962480699904282861)（by [@tetumemo](https://x.com/tetumemo)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case52/input.jpg" width="300" alt="入力画像"> | <img src="images/case52/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
ファッションのムードボードコラージュ。ポートレートの周りに、モデルが着用している個々のアイテムの切り抜きを配置してください。遊び心のあるマーカー風のフォントで手書きのメモやスケッチを追加し、各アイテムのブランド名と出典を英語で記載してください。全体の美的感覚は、創造的で可愛いものにしてください。
```

<!-- 例 53: 精巧で可愛い製品写真（by @azed_ai） -->
### 例 53: [精巧で可愛い製品写真](https://x.com/azed_ai/status/1962878353784066342)（by [@azed_ai](https://x.com/azed_ai)）

| 出力 |
|:---:|
| <img src="images/case53/output.jpg" width="300" alt="出力結果"> |

**プロンプト:**

```
リアルなミニチュアの[製品]を人の親指と人差し指で繊細に持っている高解像度の広告写真。背景は清潔で白く、スタジオ照明で、柔らかな影があります。手は手入れが行き届いており、自然な肌色で、製品の形とディテールを強調するように配置されています。製品は非常に小さく見えますが、非常に詳細でブランドも正確で、浅い被写界深度でフレームの中央に配置されています。高級製品写真とミニマリストな商業スタイルを模倣しています。
```

> [!NOTE]
> **`[角括弧]`内のテキストを、表示したい製品名に変更してください。**

<!-- 例 54: アニメの像を現実世界に配置（by @riddi0908） -->
### 例 54: [アニメの像を現実世界に配置](https://x.com/riddi0908/status/1963758463135412699)（by [@riddi0908](https://x.com/riddi0908)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case54/input.jpg" width="300" alt="入力画像"> | <img src="images/case54/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
リアルな写真作品。この人物の巨大な像が東京の中心部の広場に設置され、人々がそれを見上げています。
```

<!-- 例 55: 痛車の作成（by @riddi0908） -->
### 例 55: [痛車の作成](https://x.com/riddi0908/status/1963422536819249239)（by [@riddi0908](https://x.com/riddi0908)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case55/input.jpg" width="300" alt="入力画像"> | <img src="images/case55/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
有名な観光地や景勝地で撮影された、アニメスタイルのキャラクターアートワークを痛車（ペイントカー）デザインとして施したスポーティな車のプロフェッショナルな写真を作成してください。車には、シンプルでクリーンなデザイン構成の、大きくて目立つアニメキャラクターのイラストが描かれています。キャラクターアートワークは、大胆な色と鮮明なディテールを持つ鮮やかなアニメアートスタイルで描かれるべきです。車のスポーティな外観とキャラクターアートワークの両方を引き立てる、良好な自然光のある有名な観光地や景勝地に車両を配置してください。プロの自動車写真技術と適切な被写界深度を用いて、痛車のデザインを際立たせつつ、観光の魅力を高めるために景色の背景を取り入れてください。プロモーションや愛好家向けのマーケティング資料に適しています。
```

<!-- 例 56: 漫画の構図（by @namaedousiyoka） -->
### 例 56: [漫画の構図](https://x.com/namaedousiyoka/status/1962461786181161340)（by [@namaedousiyoka](https://x.com/namaedousiyoka)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case56/input.jpg" width="200" alt="入力画像"> <img src="images/case56/input2.jpg" width="200" alt="入力画像">| <img src="images/case56/output.jpg" width="300" alt="出力結果"> |

**入力:** キャラクターの参照画像とシーンの構図の参照画像をアップロードします。

<!-- 例 57: 漫画風スタイルへの変換（by @nobisiro_2023） -->
### 例 57: [漫画風スタイルへの変換](https://x.com/nobisiro_2023/status/1961231347986698371)（by [@nobisiro_2023](https://x.com/nobisiro_2023)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case57/input.jpg" width="300" alt="入力画像"> |<img src="images/case57/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
入力された写真を白黒の漫画風線画に変換してください。
```

<!-- 例 58: アイソメトリックなホログラム図（by @tetumemo） -->
### 例 58: [アイソメトリックなホログラム図](https://x.com/tetumemo/status/1964574226155000312)（by [@tetumemo](https://x.com/tetumemo)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case58/input.jpg" width="300" alt="入力画像"> |<img src="images/case58/output.jpg" width="300" alt="出力結果"> |

**入力:** 線画の参照画像をアップロードします。

**プロンプト:**

```
アップロードされた画像に基づいて、ワイヤーフレームの線のみを使用してホログラム化してください。
```

<!-- 例 59: マインクラフト風の風景生成（by @tetumemo） -->
### 例 59: [マインクラフト風の風景生成](https://x.com/tetumemo/status/1964860047705743700)（by [@tetumemo](https://x.com/tetumemo)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case59/input.jpg" width="300" alt="入力画像"> |<img src="images/case59/output.jpg" width="300" alt="出力結果"> |

**入力:** Googleマップの参照画像をアップロードします。

**プロンプト:**

```
この場所のランドマークを、ゲーム「マインクラフト」のHD-2Dスタイルのアイソメトリック画像（建物のみ）にしてください。
```

<!-- 例 60: マテリアル球の質感を適用（by @ZHO_ZHO_ZHO） -->
### 例 60: [マテリアル球の質感を適用](https://x.com/ZHO_ZHO_ZHO/status/1964995347505352794)（by [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)）

| 例 |
|:---:|
| <img src="images/case60/case.jpg" width="300" alt="例"> |

**入力:** 参照画像とマテリアル球の画像をアップロードします。

**プロンプト:**

```
図2の質感を、図1のロゴに適用してください。3D立体で表現し、C4Dでレンダリングしたような、単色の背景にしてください。
```

<!-- 例 61: 間取り図の3Dレンダリング（by @op7418） -->
### 例 61: [間取り図の3Dレンダリング](https://x.com/op7418/status/1961329148271513695)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case61/input.jpg" width="300" alt="入力画像"> |<img src="images/case61/output.jpg" width="300" alt="出力結果"> |

**入力:** 間取り図の参照画像をアップロードします。

**プロンプト:**

```
この住宅の間取り図を、家のアイソメトリックなフォトリアル3Dレンダリングに変換してください。
```

<!-- 例 62: カメラパラメータの再設定（by @hckinz） -->
### 例 62: [カメラパラメータの再設定](https://x.com/hckinz/status/1962803203063586895)（by [@hckinz](https://x.com/hckinz)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case62/input.jpg" width="300" alt="入力画像"> |<img src="images/case62/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
RAW-ISO [100] - [F2.8-1/200 24mm] 設定
```

> [!NOTE]
> **`[角括弧]`内の値を、希望するカメラパラメータに変更してください。**

<!-- 例 63: 証明写真の作成（by @songguoxiansen） -->
### 例 63: [証明写真の作成](https://x.com/songguoxiansen/status/1963602241610551609)（by [@songguoxiansen](https://x.com/songguoxiansen)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case63/input.jpg" width="300" alt="入力画像"> |<img src="images/case63/output.jpg" width="300" alt="出力結果"> |

**入力:** 人物の参照画像をアップロードします。

**プロンプト:**

```
画像の人物の頭部を切り取って、2インチの証明写真を作成してください。要件：
  1. 青色の背景
  2. プロフェッショナルな正装
  3. 正面顔
  4. 微笑み
```

<!-- 例 64: A6サイズの飛び出すカード（by @Gdgtify） -->
### 例 64: [A6サイズの飛び出すカード](https://x.com/Gdgtify/status/19649795223709287319)（by [@Gdgtify](https://x.com/Gdgtify)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case64/input.jpg" width="300" alt="入力画像"> |<img src="images/case64/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
A6サイズの折りたたみカードを描いてください。開くと、ミニチュアの紙の庭と盆栽の木がある完全な3D球形の小さな家が現れます。
```

<!-- 例 65: チェスセットのデザイン（by @Gdgtify） -->
### 例 65: [チェスセットのデザイン](https://x.com/Gdgtify/status/1964679042994442454)（by [@Gdgtify](https://x.com/Gdgtify)）

| 例 |
|:---:|
| <img src="images/case65/case.jpg" width="300" alt="例"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
この画像にインスパイアされたチェス盤と3Dプリント可能なチェスの駒を描いてください。
```

<!-- 例 66: 時代を比較する分割写真（by @fofrAI） -->
### 例 66: [時代を比較する分割写真](https://x.com/fofrAI/status/1964818395381248397)（by [@fofrAI](https://x.com/fofrAI)）

| 例 |
|:---:|
| <img src="images/case66/case.jpg" width="300" alt="例"> |

**プロンプト:**

```
寝室の写真で、中央で分割されています。左側は2018年、右側は1964年の同じ部屋です。
```

<!-- 例 67: ジュエリーコレクションのデザイン（by @Gdgtify） -->
### 例 67: [ジュエリーコレクションのデザイン](https://x.com/Gdgtify/status/1964419331342909777)（by [@Gdgtify](https://x.com/Gdgtify)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case67/input.jpg" width="300" alt="入力画像"> |<img src="images/case67/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
この画像を5点のジュエリーコレクションに変えてください。
```

<!-- 例 68: グッズデザイン（by @0xFramer） -->
### 例 68: [グッズデザイン](https://x.com/0xFramer/status/1964992117324886349)（by [@0xFramer](https://x.com/0xFramer)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case68/input.jpg" width="300" alt="入力画像"> |<img src="images/case68/output.jpg" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードします。

**プロンプト:**

```
このキャラクター画像を使ってグッズを作成してください。
```

<!-- 例 69: モデルホログラム投影（by @UNIBRACITY） -->
### 例69：[モデルホログラム投影](https://x.com/UNIBRACITY/status/1966122746288681461)（by [@UNIBRACITY](https://x.com/UNIBRACITY)）

| 出力 |
|:---:|
| <img src="images/case69/output.png" width="300" alt="出力結果"> |

**プロンプト:**

```
超リアルな製品写真。
主体：バーチャルホログラフィックキャラクター [CHARACTER] が、直径120mmの円形ホログラムプロジェクターの上に現代的なデスクで浮遊している。

投影ソースルール：
- 入力参照オブジェクトが3Dオブジェクトの場合、プロジェクターの隣にデスクトップ3Dスキャナーを配置する。
参照オブジェクトをスキャンプレートに置く。
プロジェクター上のホログラムはスキャンされたオブジェクトから生成される。
- 入力参照オブジェクトが2D画像の場合、デスク上にモニター付きの現代的なPCを置く。
モニター画面に参照画像を表示する。
プロジェクター上のホログラムはその画面内容から生成される。

ホログラムレンダリングルール：
- キャラクターは常に半透明のボリューム画像として表示され、背景がうっすら見える。
- ビームなし、粒子なし、実体彫像の表面なし。
- バランスの取れた解剖構造（頭身比1/7～1/8）、正しい比率。
- 自然なポーズ、明確なシルエット。
- 髪、服のしわ、アクセサリーは見えるが半透明。
- 顔は鮮明で表情豊か、1000ピクセルのクロップでも判読可能。
- 著作権キャラクター、ブランドデザイン、IPロゴなし。

環境：現代的なオフィスデスク、プロジェクターベース + 補助機器（スキャナーまたはモニター）。
カメラ：85～100mmレンズ、3/4ヒーローアングル、目の高さ、f/11～f/16、ISO100、三脚。
照明：デスクの柔らかい照明；ホログラム人物はボリュームライトのみで定義。
背景：シームレスな黒いスタジオ、微妙な反射。

出力：4:5、2048×2560。

ネガティブ：文字なし、透かしなし、ロゴなし、ブランドなし、著作権キャラクター、シリーズIP、商標デザイン、樹脂、PVC、実体彫像、不透明な表面、玩具のような光沢、ビーム、スキャンライン、点、歪み、余分な数字なし。
サンプリング：決定論的、Seed=12345、Temperature=0。
```

> [!NOTE]  
> **[角括弧] 内の文字を入力するキャラクターに置き換えてください**

<!-- 例 70: 巨大人物の足場（by @songguoxiansen） -->
### 例70：[巨大人物の足場](https://x.com/songguoxiansen/status/1965960484684968234)（by [@songguoxiansen](https://x.com/songguoxiansen)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case70/input.png" width="300" alt="入力画像"> | <img src="images/case70/output.png" width="300" alt="出力結果"> |

**入力:** 人物の参照画像をアップロードする必要があります。

**プロンプト:**

```
画像の中の人物が立って自撮りしている超写実的な3Dレンダリング。 
巨大な人物の全身を取り囲むように巨大な足場が組まれており、その上で多くの小さな建設作業員が作業している。 
シーンは都市の広場に設定され、周囲には現代的な建物、走行中の車（乗用車、バス）、歩行者があり、 
さらに晴れ渡った明るい青空が広がっている。 
全体のディテールは豊かで、写真のようなリアルな質感を示し、映画的なライティング効果が採用されている。
```

<!-- 例 71: リモートセンシング画像の建物抽出（by @lehua555） -->
### 例71：[リモートセンシング画像の建物抽出](https://x.com/lehua555/status/1966124995949863310)（by [@lehua555](https://x.com/lehua555)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case71/input.png" width="300" alt="入力画像"> | <img src="images/case71/output.png" width="300" alt="出力結果"> |

**入力:** リモートセンシング画像をアップロードする必要があります。

**プロンプト:**

```
画像から建物以外の部分を削除する。
```

<!-- 例 72: 部品抽出（by @tetumemo） -->
### 例72：[部品抽出](https://x.com/tetumemo/status/1965721026849018141)（by [@tetumemo](https://x.com/tetumemo)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case72/input.png" width="300" alt="入力画像"> | <img src="images/case72/output.png" width="300" alt="出力結果"> |

**入力:** モデルの画像をアップロードする必要があります。

**プロンプト:**

```
各部品を切り出して、ホログラムを保持したモデルシートを作成する。
```

<!-- 例 73: ハンバーガーの具材を取り除く（by @bind_lux） -->
### 例73：[ハンバーガーの具材を取り除く](https://x.com/bind_lux/status/1965869157125402654)（by [@bind_lux](https://x.com/bind_lux)、本ケース提供：[@jeanlucaslima](https://github.com/jeanlucaslima)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case73/input.jpg" width="300" alt="入力画像"> | <img src="images/case73/output.jpg" width="300" alt="出力結果"> |

**入力:** ハンバーガーの画像をアップロードする必要があります。

**プロンプト:**

```
ハンバーガーの中のすべての具材を取り出し、上下のバンズだけを残す。 
バンズの間に隙間を空けて、中身がまだあるかのように見せる。
```

<!-- 例 74: 画像の高解像度修復（by @op7418） -->
### 例74：[画像の高解像度修復](https://x.com/op7418/status/1960540798573011209)（by [@op7418](https://x.com/op7418)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case74/input.png" width="300" alt="入力画像"> | <img src="images/case74/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
この古い画像の解像度を向上させ、適切なテクスチャディテールを追加し、現代的なアニメ技術で再解釈する。
```

<!-- 例 75: 画像からミニチュアシーン生成（by @techhalla） -->
### 例75：[画像からミニチュアシーン生成](https://x.com/techhalla/status/1962088250199163285)（by [@techhalla](https://x.com/techhalla)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case75/input.png" width="300" alt="入力画像"> | <img src="images/case75/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
画像をアイソメトリックビューに変換する。
```

<!-- 例 76: 科学普及マンガ（by @op7418） -->
### 例76：[科学普及マンガ](https://x.com/op7418/status/1961811274683310110)（by [@op7418](https://x.com/op7418)）

| 出力 |
|:---:|
| <img src="images/case76/output.png" width="300" alt="出力結果"> |

**プロンプト:**

```
16:9 の落書き風イラストを複数生成してください。中学生に「未来」という概念を説明するものです。 
画像は一貫したカラフルな太い色鉛筆の手描き風スタイルで、情報量が豊富であること。 
英語のテキストを含め、単色の背景を使用し、カードの周囲にアウトラインを描き、 
統一されたタイトルを配置してください。PowerPoint プレゼンテーションのようなイメージです。
```

<!-- 例 77: カスタムキャラクターのスタンプ生成（by @vista8） -->
### 例77：[カスタムキャラクターのスタンプ生成](https://x.com/vista8/status/1966164427243458977)（by [@vista8](https://x.com/vista8)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case77/input.png" width="300" alt="入力画像"> | <img src="images/case77/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
画像2のキャラクターを使い、画像1のさまざまなポーズを基に [x] 個のスタンプを生成する。
```

> [!NOTE]  
> **[角括弧] 内の文字を必要なスタンプ数に置き換えてください**

<!-- 例 78: 食べかけの食べ物を復元（by @googlejapan） -->
### 例78：[食べかけの食べ物を復元](https://x.com/googlejapan/status/1965762180688584916)（by [@googlejapan](https://x.com/googlejapan)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case78/input.png" width="300" alt="入力画像"> | <img src="images/case78/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
半分食べられた [XX] を、食べられる前の状態に復元する。
```

> [!NOTE]  
> **[角括弧] 内の文字を入力する食べ物の名前に置き換えてください**

<!-- 例 79: 格闘ゲームのインターフェース制作（by @NanoBanana_labs） -->
### 例79：[格闘ゲームのインターフェース制作](https://x.com/NanoBanana_labs/status/1965827209534517654)（by [@NanoBanana_labs](https://x.com/NanoBanana_labs)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case79/input.png" width="300" alt="入力画像"> | <img src="images/case79/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
中速のアクションシーンを作成し、2人の主体を3/4視点で鮮明にフォーカスし、武術の格闘ポーズをとらせる。 
彼らは同じ映画的なシーンの中にいる。中央の線を取り除き、背景には紫色の異星世界にあるぼやけた崩れかけの廃墟を配置する。 
シーンは日の出の時間に撮影される。 

現代的な格闘ゲームのライフバー、モートン対デスシード。強力な必殺技。HUDスタイルの画面エフェクト。 
ライフバーにはそれぞれのキャラクターのサムネイルを追加する。クールなグロー効果！
```

<!-- 例 80: モデルの断面図（by @old_pgmrs_will） -->
### 例80：[モデルの断面図](https://x.com/old_pgmrs_will/status/1966053092371444029)（by [@old_pgmrs_will](https://x.com/old_pgmrs_will)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case80/input.png" width="300" alt="入力画像"> | <img src="images/case80/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
この車の断面図を作成し、一方の側面には完全な外部構造を表示し、もう一方には内部のエンジンと座席を表示する。 
比例を正確に保ち、ディテールをリアルに描写する。
```

<!-- 例 81: 海賊の手配書（by @AI_Kei75） -->
### 例81：[海賊の手配書](https://x.com/old_pgmrs_will/status/1966053092371444029)（by [@AI_Kei75](https://x.com/AI_Kei75)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case81/input.png" width="300" alt="入力画像"> | <img src="images/case81/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
元の画像を使用して、羊皮紙の上に海賊の手配書を描き直す。 
茶色の単色で、古びた羊皮紙の質感を持たせる。 
元の画像のスタイルとキャラクターデザインを細部まで保持し、 
大きなサイズで手配書の上部に貼り付ける。 
顔のクローズアップ。キャラクターに海賊帽をかぶせる。 

ポスターの下部に賞金額を書く。賞金額はランダムで、架空の通貨単位を使用する。 
賞金額の下に罪状を小文字で記載する。架空の言語を使用し、英語や中国語は使用しないこと。
```

<!-- 例 82: 周辺展示棚（by @tokyo_Valentine） -->
### 例82：[周辺展示棚](https://x.com/tokyo_Valentine/status/1966888938838298727)（by [@tokyo_Valentine](https://x.com/tokyo_Valentine)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case82/input.png" width="300" alt="入力画像"> | <img src="images/case82/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
このイラストの背景を削除し、フィギュアのような周辺商品にする。
画像：写真のようにリアル

場所：
日本の架空のコンビニエンスストアの棚。 
可愛くて流行的な雰囲気が、整然と並べられたイラストグッズと調和している。 
店内は夢のように明るく、ユニークで、ファンをワクワクさせる特別な空間を作り出している。

人物：
これらの周辺商品は棚に展示されている。

周辺商品：
画面中央に約50cmの大型フィギュアが2体（目立つ展示）
アクリルスタンド（原作のデフォルメ版）

デフォルメフィギュア（原作のデフォルメ版）

抱き枕（大型印刷物、目立つ展示）

パズル（キャラクターデザイン）

文房具（ノート、ペン、ファイルなど、原作のデフォルメ版）

紙製パネル（原作のデフォルメ版）

ぬいぐるみ（原作のデフォルメ版）

展示方法：
周辺商品は棚にきちんと並べられており、コンビニらしさを保ちながらもキャラクターへの愛情が感じられる。 
その陳列方法は、少女ファンたちが思わず手に取りたくなるように演出されている。

全体の雰囲気：
夢のような周辺商品販売空間。 
可愛さと流行の要素が主役であり、単なるコンビニでありながら「ファンの聖地」に仕立てられている。

解像度：4K、4000×3000ピクセル
```

<!-- 例 83: 漫画展示ブース（by @tokyo_Valentine） -->
### 例83：[漫画展示ブース](https://x.com/tokyo_Valentine/status/1967174466636792287)（by [@tokyo_Valentine](https://x.com/tokyo_Valentine)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case83/input.png" width="300" alt="入力画像"> | <img src="images/case83/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
背景を消去し、人物を以下の内容に置き換える：

コスプレイヤーとキャラクターグッズ

キャラクター/テーマ：
イラストを基にしたキャラクターグッズ

髪型、アイメイク、外見：
（キャラクター自体ではなく、グッズに注目すること。）

主役：コスプレイヤーがフィギュアを手に持ち、画面中央に立つ。

場所：
コミックマーケット（同人誌販売イベント）。 
広々としたブースにテーブルや棚が並び、グッズが陳列され、熱気と期待感に包まれている。

グッズ：
• 約100cmの大型フィギュアがブース中央に配置され、目を引く。  
• 80インチの液晶ディスプレイにキャラクターを表示。  
• アクリルスタンド  
• ミニフィギュア（デフォルメ）  
• 抱き枕（大型の全身プリント）  
• パズル（キャラクター原画を使用）  
• 文房具（ノート、ペン、クリアファイルなど）  
• デスクマット  
• ぬいぐるみ（デフォルメ）

展示/陳列：
• グッズはブース全体に整然と並べられ、統一感のある雰囲気を演出。  
• 同人誌即売会に見られるようなテーブルや棚を用いて、ファンに商品を選ばせる工夫。  
• 活気ある来場者を背景に、ブースを特別な「ファンの聖地」として演出。

全体のトーン：
夢のような販売空間。  
可愛さと流行の要素を強調しつつ、同人イベント特有の情熱を呼び起こし、「ファン活動の聖地」の雰囲気を醸成。  
人々で賑わっている。

画像品質：フォトリアル、4K（4000×3000ピクセル）
```

<!-- 例 84: 線画から落書き風イラストへ変換（by @hAru_mAki_ch） -->
### 例84：[線画から落書き風イラストへ変換](https://x.com/hAru_mAki_ch/status/1966877088365113722)（by [@hAru_mAki_ch](https://x.com/hAru_mAki_ch)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case84/input.png" width="300" alt="入力画像"> | <img src="images/case84/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
アップした塗り絵を5歳児が塗った感じにして。
```


<!-- 例 85: 現代美術展示空間（by @UNIBRACITY） -->
### 例85：[現代美術展示空間](https://x.com/UNIBRACITY/status/1967129632093991164)（by [@UNIBRACITY](https://x.com/UNIBRACITY)）

| サンプル |
|:---:|
| <img src="images/case85/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
参照画像をテーマにした前衛的な現代美術の展示空間。
ホール全体（20.0 m × 20.0 m × 8.0 m）は、建築・照明・床・壁・天井すべてが作品表現の一部として統合されている。

最奥には幅20 m・高さ8 mの大壁が立ち、その中央に参照画像のモチーフが巨大な芸術的造形として示される。像は鮮明かつ立体的で、観客に向かって浮かび上がり、空間の中心点となる。

大壁中央下には、システムが生成する**作品題名（Title）**が展覧会名として刻まれたプレートが設置される。題名は抽象的・象徴的・詩的で、現代美術作品として成立するものであること。金額表示は行わない。

床は反射率0.35〜0.40の磨きグラニット。表面には参照画像に由来するパターンや光が重なり、来館者の足取りに呼応するように空間全体と響き合う。点字ブロックは同系色で溶け込みながらも凹凸高さ5 mmで確実に触知可能。入口から大壁まで直線的に連続し、作品前に停止点を形成。観賞後は自然に右側の開口（幅3 m × 高さ3 m）へ導かれる。非常時には床レベル非常灯が1 lxを保証する。

左右の壁・天井は、それぞれ異なる解釈で参照画像の要素を抽象化して表現しており、構造自体が作品となっている。色彩、形態、光の動きが空間全体をひとつの芸術体験へと統合する。

来館者は8〜25人。全員が大壁方向を向き、導線に沿って進みながら停止点で立ち止まる。入口方向を振り返る者はいない。スタッフは大壁右開口付近に一名のみ配置。全員の顔は必ずぼかされ匿名化される。

構図は安定し、中央消失点は必ず大壁中央。垂直は±0.5°以内。床反射は正確で、人体は自然。手指は必ず5本、両目は対称で差異3%以内。布は直線保持され歪みはゼロ。

禁止事項：参照画像と無関係な要素、点字ブロックの欠落や分断、入口を向いた来館者、ロゴや透かし、群衆過密、玩具的光沢、2D的な平板投影、ネオングロー、ティールオレンジ調色、過飽和、透視崩壊、反射不整合、解剖異常、余剰肢、歪んだ顔、過剰輪郭、縞模様、ビネット。

DoD：会場全体が参照画像をテーマとした現代美術作品として成立し、最奥の造形を中心に空間全体が統一された体験を形成する。点字ブロックは導線と完全に連動し、停止点を明確に形成。観客は空間そのものに没入し、再生成でもSSIM 0.95以上で安定。
```

<!-- 例 86: ダークゴシックタロットカード（by @ImperfectEngel） -->
### 例86：[ダークゴシックタロットカード](https://x.com/ImperfectEngel/status/1961833518163481001)（by [@ImperfectEngel](https://x.com/ImperfectEngel)）

| サンプル |
|:---:|
| <img src="images/case86/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
この画像をもとに、私を主人公としたダークゴシック風のタロットカードを生成する。 
[「AIアーティスト - Shira」] と [コーヒー、ピンクのリボンをつけた白くてふわふわの太った猫、ノートパソコン、スマートフォン、ヘッドフォン] をシンボルとして含め、 
憂鬱な影、精巧なゴシック調の枠、神秘的なダークファンタジーの雰囲気を加える。
```

> [!NOTE]  
> **[角括弧] 内の文字を必要な設定に置き換えてください**

<!-- 例 88: ガラス瓶の記念品（by @NanoBanana_labs） -->
### 例88：[ガラス瓶の記念品](https://x.com/NanoBanana_labs/status/1967191346017673334)（by [@NanoBanana_labs](https://x.com/NanoBanana_labs)）

| サンプル |
|:---:|
| <img src="images/case88/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
1/7スケールの商用コレクションフィギュアを、写真の人物を原型として高度にリアルなスタイルで制作する。 
フィギュアは精巧なビーチ環境に配置され、砂浜、貝殻、優しい波が組み合わさっている。 
全体のディスプレイスタンドは透明な記念ガラス瓶に封入され、高級感のあるミニチュア立体モデル効果を示し、リアルな光と影の効果を持つ。
```

<!-- 例 89: ミニチュアショップ（by @NanoBanana_labs） -->
### 例89：[ミニチュアショップ](https://x.com/NanoBanana_labs/status/1966791308321910922)（by [@NanoBanana_labs](https://x.com/NanoBanana_labs)）

| 出力 |
|:---:|
| <img src="images/case89/output.png" width="300" alt="出力結果"> |

**プロンプト:**

```
[ブランド] のミニチュア立体モデルショップ。 
屋根は特大の [製品] で作られ、窓の上には巨大な [ブランド] ロゴがある。 
店主は客に [製品] を手渡しており、地面には多数の [製品] が散らばっている。 
ハンドメイドのポリマークレイ造形、スタジオでのマクロ撮影、柔らかな照明、浅い被写界深度、縦長 3:4。
```

> [!NOTE]  
> **[角括弧] 内の文字を必要な製品に置き換えてください**

<!-- 例 90: Vtuberになる（by @AI_Kei75） -->
### 例90：[Vtuberになる](https://x.com/AI_Kei75/status/1967490141578236329)（by [@AI_Kei75](https://x.com/AI_Kei75)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case90/input.png" width="300" alt="入力画像"> | <img src="images/case90/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
元の画像を使用して、バーチャルVtuberとその配信画面を作成する。 
Vtuberの髪型と衣装は原図を忠実に再現する。 
Vtuberの映像は2.5D画質で、完全に原図のスタイルを再現する必要はないが、適度な立体感を持たせる。 
Vtuberの表情やポーズは原図と異なってもよい。Vtuberにゲームコントローラーを持たせる。 

Vtuberの上半身のみを画面右下に配置する。プレイ中のゲーム配信画面を画面中央に配置する。チャット画面を画面左側に配置する。 
ゲーム画面の比率は大きく設定し、Vtuberの上半身は小さめに表示する。 
原図の背景やポーズは完全に無視する。 
画面の上下には仮想の配信プラットフォームとブラウザUIを追加する。 
生成される画像の縦横比は原画像の縦横比に依存しない。
```

<!-- 例 91: 駅の映画ポスター（by @AI_Kei75） -->
### 例91：[駅の映画ポスター](https://x.com/AI_Kei75/status/1967498630467625127)（by [@AI_Kei75](https://x.com/AI_Kei75)）

| 入力 | 出力 |
|:---:|:---:|
| <img src="images/case91/input.png" width="300" alt="入力画像"> | <img src="images/case91/output.png" width="300" alt="出力結果"> |

**入力:** 参照画像をアップロードする必要があります。

**プロンプト:**

```
元の画像を使用して映画ポスターを制作する。映画のジャンルは元画像の雰囲気に基づいて決定される。 
元画像がアニメでも実写でも、そのスタイルとキャラクターデザインは可能な限り忠実に保持する。 
ただし、ポスターのデザインに応じてポーズや表情は調整される場合がある。さらに、他の人物や物体が追加されることもある。 

最終的に生成される画像はフォトリアルな品質を持つが、ポスターデザインは元画像に基づいて作成される。 
ポスターが貼られる日本の駅の地下通路のシーンはリアルに再現され、通路を歩く人々も追加される。 
ポスターの反射角度は調整され、よりリアルに見えるようにする。
```


## 🙏 謝辞

このリポジトリは、[awesome-gpt4o-images](https://github.com/jamez-bondos/awesome-gpt4o-images)に触発されて作成されました。リポジトリ内の様々な事例は、AIコミュニティの皆様の共有によって成り立っています。すべての事例の貢献者の皆様に心から感謝申し上げます。

素晴らしい作品を共有してくださった以下のユーザーの皆様に感謝します。彼らのプロフィールもぜひご覧ください：

- [@ZHO_ZHO_ZHO](https://x.com/ZHO_ZHO_ZHO)
- [@tokumin](https://x.com/tokumin)
- [@bilawalsidhu](https://x.com/bilawalsidhu)
- [@Zieeett](https://x.com/Zieeett)
- [@AmirMushich](https://x.com/AmirMushich)
- [@MrDavids1](https://x.com/MrDavids1)
- [@op7418](https://x.com/op7418)
- [@黄建同学](https://weibo.com/u/5648162302)
- [@balconychy](https://x.com/balconychy)
- [@berryxia_ai](https://x.com/berryxia_ai)
- [@umesh_ai](https://x.com/umesh_ai)
- [@Gdgtify](https://x.com/Gdgtify)
- [@302.AI](https://medium.com/@302.AI)
- [@Gorden Sun](https://www.xiaohongshu.com/user/profile/632e72f900000000230397fe)
- [@GeminiApp](https://x.com/GeminiApp)
- [@skirano](https://x.com/skirano)
- [@Error_HTTP_404](https://x.com/Error_HTTP_404)
- [@arrakis_ai](https://x.com/arrakis_ai)
- [@AiMachete](https://x.com/AiMachete)
- [@icreatelife](https://x.com/icreatelife)
- [@demishassabis](https://x.com/demishassabis)
- [@TechHallo](https://x.com/techhalla)
- [@tapehead_Lab](https://x.com/tapehead_Lab)
- [@AIimagined](https://x.com/AIimagined)
- [@0xFramer](https://x.com/0xFramer)
- [@fofrAI](https://x.com/fofrAI)
- [@songguoxiansen](https://x.com/songguoxiansen)
- [@hckinz](https://x.com/hckinz)
- [@tetumemo](https://x.com/tetumemo)
- [@nobisiro_2023](https://x.com/nobisiro_2023)
- [@namaedousiyoka](https://x.com/namaedousiyoka)
- [@riddi0908](https://x.com/riddi0908)
- [@azed_ai](https://x.com/azed_ai)
- [@bwabbage](https://x.com/bwabbage)
- [@nglprz](https://x.com/icreatelife)
- [@UNIBRACITY](https://x.com/UNIBRACITY)
- [@lehua555](https://x.com/lehua555)
- [@bind_lux](https://x.com/bind_lux)
- [@techhalla](https://x.com/techhalla)
- [@vista8](https://x.com/vista8)
- [@googlejapan](https://x.com/googlejapan)
- [@NanoBanana_labs](https://x.com/NanoBanana_labs)
- [@old_pgmrs_will](https://x.com/old_pgmrs_will)
- [@AI_Kei75](https://x.com/AI_Kei75)
- [@tokyo_Valentine](https://x.com/tokyo_Valentine)
- [@ImperfectEngel](https://x.com/ImperfectEngel)

*すべての事例が原作者のものであることを保証するものではありません。もしご迷惑をおかけした場合は、修正のためお気軽にご連絡ください。*

私たちが収集した事例は、考えられるすべての応用シナリオを網羅しているわけではありません。もし他にも面白い発見がありましたら🔍、ぜひご連絡ください。より多くの創造性を紹介できることを楽しみにしています📧！

[![Star History Chart](https://api.star-history.com/svg?repos=PicoTrex/Awesome-Nano-Banana-images&type=Date)](https://www.star-history.com/#PicoTrex/Awesome-Nano-Banana-images&Date)
