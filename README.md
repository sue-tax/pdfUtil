# PDFファイル操作ユーティリティ

　ＰＤＦファイルを右クリックして、回転、分割、結合ができます。

　Exploreやデスクトップ上で、ＰＤＦファイルを右クリックして、「送る」の中から、PdfRight.exe などを選択してください。

## インストール方法

　ダウンロードしたファイルを、「SendTo」用のフォルダにコピーします。

※Windowsキー＋Rで、「ファイル名を指定して実行」ダイアログを開きます。

　「shell:sendto」を入力して、「OK」をクリックします。

　開いたフォルダが「SendTo」用のフォルダです。

　C:\Users\xxxxxxx\AppData\Roaming\Microsoft\Windows\SendToのようなフォルダ名で、プリンタのショートカットなどが入っています。

　そのフォルダにダウンロードしたファイルをコピーしてください。

　元のＰＤＦファイルを削除しますので、まずはＰＤＦファイルをコピーして、お試しください。

## ファイル内容
PdfRight.exe       右回転（複数ページ、複数ファイルに対応）


PdfRightU.exe      右回転（複数ページ、複数ファイルに対応）　※保護ファイル対応


PdfLeft.exe        左回転（複数ページ、複数ファイルに対応）


PdfLeftU.exe      左回転（複数ページ、複数ファイルに対応）　※保護ファイル対応


PdfUpsideDown.exe  １８０度回転（複数ページ、複数ファイルに対応）


PdfUpsideDownU.exe      １８０度回転（複数ページ、複数ファイルに対応）　※保護ファイル対応


PdfSplit.exe       １ページずつに分割（複数ファイル非対応）


PdfSplitU.exe      １ページずつに分割（複数ファイル非対応） ※保護ファイル対応


PdfMerge.exe       複数ファイルを結合（SHIFTを押しながらクリックし複数選択）

　最後のページとなるファイルから、最初のページとなるファイルまでを、SHIFTを押しながら、順番に左クリックします。

　その後、右クリックで、pdefMerge.exeを選択します。

　※ファイルの順番が違っている場合がありますので、念のため、結合後に確認してください。

PdfMergeU.exe      複数ファイルを結合（SHIFTを押しながらクリックし複数選択） ※保護ファイル対応


PdfDevide.exe      ２つに分割（複数ファイル非対応）

　ダイアログに分割する後半部分の先頭ページ数を入力します。

　６ページを半分に分けるならば、4を入力。

　元のファイルは削除、２つのファイルができます。

　６ページの場合に、1や7を入力すると、何もしません。


PdfMark.exe       ＰＤＦファイルの先頭ページの左上に、「済」マークを付けます。

PdfUnlock.exe　　ＰＤＦファイルの保護を解除します。

PdfMemo.exe　　クリップボード内の文字列を、ＰＤＦファイルの左上に注釈として書き込みます。（処理後に、プレビューで注釈が表示されない。他のソフトで開いて保存したら、プレビューでも表示される）

PdfMemoAI.exe　　クリップボード内の文字列を、ＰＤＦファイルの左上に注釈として書き込みます。（処理後に、プレビューで注釈が表示されるが、フォント指定が上手くできず、フォントが今一）


※ファイル名を「右回転.exe」などに変更しても、動作します。

 ## 「送る」を省く 
　レジストリをいじれば、右クリックから直接選択することも可能です。
　ただし、くれぐれも自己責任でお願いします。

~~https://www.billionwallet.com/goods/windows10/win10_mouse_rightclick.html~~

~~マウス右クリックで表示されるメニューにアイテムを追加し~~

~~関連ファイルを素早く開く方法 - Windows 10~~

　~~こちらの記事を参考に、~~
~~"C:\WINDOWS\system32\mspaint.exe" "%1"~~
~~の代わりに、~~

https://it-study.info/pulldownmenu-item-add/

　こちらの記事を参考に、
"C:\Windows\System32\WindowsPowerShell\v1.0\powershell_ise.exe" "%1"
の代わりに、
"C:\Users\xxxxxxx\AppData\Roaming\Microsoft\Windows\SendTo\PdfRight.exe" "%1"
を設定すれば、できるようだ。

"C:\Users\xxxxxxx\AppData\Roaming\Microsoft\Windows\SendTo\PdfRightU.exe" "%1" "%2" "%3" "%4" "%5" "%6" "%7" "%8" "%9"
のようにすれば、複数ファイルを指定可能になる。（PdfMergeは、できません）
