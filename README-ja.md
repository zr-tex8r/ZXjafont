ZXjafont パッケージバンドル
===========================

LaTeX： 一般的な和文フォント設定のプリセット

XeLaTeX + fontspec でのフォントファミリ名を直接指定する方式は「好きな
フォントを指定する」という点では、 pLaTeX よりも格段に使い易いが、日本語
を扱うためには必ず何らかの設定を行う必要があり、これが煩わしく感じられる
場合もある。本パッケージでは、pLaTeX において一般的に行われている設定を
予め用意しておいて、簡単に呼び出せるようにしている。

### 前提環境

  - TeX 処理系： XeLaTeX
  - 前提パッケージ： fontspec

### 本ソフトウェアの作者のサイト

  - En toi Pythmeni tes TeXnopoleos ～電脳世界の奥底にて～  
    <http://zrbabbler.sp.land.to/>

  - 以下のページに一部機能の使用例を紹介した。  
    「ZXjafont パッケージ」
    <http://zrbabbler.sp.land.to/zxjafont.html>

### インストール

TDS 1.1 に従ったシステムでは、各ファイルを次の場所に移動する。

  - `*.sty`   → $TEXMF/tex/xelatex/zxjafont/

W32TeX を C:\usr\local にインストールした場合は次のようになる。

  - `*.sty`   → C:\usr\local\share\texmf-local\tex\xelatex\zxjafont

### ライセンス

MIT ライセンス

更新履歴
--------

  * Version 0.3  [2015/05/08]
      - プリセット設定を pxchfon のものに合わせた。
  * Version 0.2a [2013/01/28]
      - 新版の zxjatype への対応。
  * Version 0.2  [2009/12/22]
      - 最初の公開版。

--------------------
Takayuki YATO (aka. "ZR")  
http://zrbabbler.sp.land.to/