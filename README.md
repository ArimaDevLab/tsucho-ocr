# 通帳OCR転記ツール（Webお試し版）

https://arimadevlab.github.io/tsucho-ocr/

通帳のスキャン画像・PDFから、日付・摘要・支払金額・預り金額・差引残高を読み取り、CSVに書き出すツールです。
弥生会計・freee・マネーフォワード クラウド向けの仕訳インポート形式でも出力できます。

- 画像の読み取りは、ブラウザの中（WebAssembly）だけで行います。通帳画像やOCR結果を外部へ送信しません。
- このページは Content-Security-Policy で、このサイト以外への通信を禁止しています。
- 「サンプル通帳画像で試す」で、自分の通帳を使わずに動きを確認できます。
- お試し版のため、画面表示・CSV書き出し・コピー・作業保存は先頭10行までです。

## 無料モニター募集中
全行を変換でき、ネットにつながないパソコンでも使える製品版（ZIP）を、会計事務所・経理のご担当者さまに無料でお渡ししています。
arima.dev.lab@outlook.jp までご連絡ください。

マニュアル: manual.pdf ／ 利用規約: terms_of_use.pdf ／ 免責事項: DISCLAIMER.txt ／ ライセンス: THIRD_PARTY_LICENSES.txt

つくった人: Arima Dev Lab（https://arima-dev-lab.vercel.app/）
