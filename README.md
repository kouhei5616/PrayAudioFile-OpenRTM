# PrayAudioFile-OpenRTM<br>

## 概要<br>
オーディオファイルを再生するOpenRTMコンポーネントです。<br>
pythonのwaveモジュールを使用しています。（既にファイルの中に組み込まれています）<br>

## 必要なもの<br>
・Linux/Windows/MacOS搭載のPC<br>
・オーディオファイル<br>
・スピーカー<br>

## 使い方<br>
１．PrayAudioFile.pyを起動する。<br>

２．OpenRTMでパラメータの設定・接続・アクティブ化する。<br>

## コンポーネントの説明<br>
・PlayAudioFile<br>
　pythonで作成したオーディオファイルを再生するコンポーネント<br>
　入力：filename_input　オーディオファイル名<br>
　出力：なし<br>
　パラメータ：なし<br>

・Test2<br>
　PlayAudioFileコンポーネントをテストする用のコンポーネント<br>
　入力：なし<br>
　出力：filename_output　オーディオファイル名<br>
　パラメータ：なし<br>

