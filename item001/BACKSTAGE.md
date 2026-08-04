## 概要
管理対象にQRコードを割り当て、カメラで撮影してURLを取得し、関連情報を獲得する。
## 仕組み
- 関連情報保管メカニズム
- QRコード作成メカニズム

- 1. モノのID,名前、対応ソフトのURLのリストを作成してgithubに登録してURLを取得する。
2. そのURLのQRコードを外部サイト(https://qr.quel.jp)で作成する。
3. QRコードを95pics X 95picsで作成し、拡大率100%として25mm X 25mm で印刷し、モノに張り付ける。
4. 実行時にはモノの写真をとり、URLを取得し、そのURLにアクセスする。

このgithubへのアクセス：Googleのアクセスによる
githubのURL: https://bamdn300-lab.github.io
Repositoryの名前：my-items
folderの名前：item001など
itemの名前：item001.htmlなど
