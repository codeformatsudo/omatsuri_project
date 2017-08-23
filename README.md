# お祭りサイトの構築キット

## Description
　　dataのcsvを入れ替えるだけで簡単にページが作成できます。

## Demo
  https://codeformatsudo.github.io/omatsuri_project/
		
## Variation Demo
  https://codeformatsudo.github.io/omaturi_project_demo/

## Usage
### GitHub Pagesでサイトを公開する
* forkしたリポジトリのdocsフォルダをSettingsのGitHub PagesのSouceで指定します。

### 情報の掲載
* docsのdataフォルダにある各csvやtxtを編集します。
* 必要のないファイルでも削除しないでください。
* 各csvファイルの1行目の項目は削除せず、2行目以降で必要がない場合は空のセルにしてください。
* イベントスケジュール（event-1.csvとevent-2.csv）は項目がありません。必要ない場合はテキストをすべて削除してください。
* テンプレートの基本色は「赤」「ピンク」「黒」「黄色」です。info.csvの基本色項目にお好みの色を入力してください。
* Twitterのハッシュタグでツイートした内容を、左下の「お知らせボタン」からスライドインした部分に表示できます。検索ウィジェットを作成し、コードをtwitterWidget.txtに貼り付けてください。

### コードの修正する場合
* 修正はresourceフォルダ内で作業してください。gulpでdocsに出力しています。