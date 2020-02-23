ZXjafont Package
================

LaTeX: Set up Japanese font families for XeLaTeX

Font selection using fontspec package is very flexible and powerful.
But users who are used to pLaTeX often feel the setting bothersome,
as there is no default working font setting (that involves Japanese
fonts) and they always must give one. This package prepares some
popular font settings as “presets” and allows users to use them
simply by referring to their name.

### SYSTEM REQUIREMENTS

  * TeX format: LaTeX.
  * TeX engine: XeTeX.
  * Prerequisite packages:
      - fontspec

### INSTALLATION

Move the files as follows (in a system compliant to TDS 1.1):

  - `*.sty`   → $TEXMF/tex/xelatex/zxjafont/

And rehash your TEXMF trees if necessary.

### LICENSE

This package is distributed under the MIT License.


zxjafont Package ー main
------------------------

Please refer to the manual `zxjafont.pdf` (in Japanese) for detail.


Revision History
----------------

  * Version 1.2  〈2020/02/24〉
      - New option: `expert`.
      - More options for compatibility with luatexja-preset.
      - Adjustment of presets involving Moga Fonts.
  * Version 1.1b 〈2020/02/22〉
      - More options for compatibility with luatexja-preset.
  * Version 1.1a 〈2020/02/15〉
      - Adjustment for the revision of NFSS.
  * Version 1.1  〈2020/02/08〉
      - Now `prop` is available even in Japanese-font mode.
  * Version 1.0  〈2020/02/02〉
      - Now multiweight presets offer three weights per family. New
        option `(no)threeweight` is added.
      - Now use of xeCJK activates the Japanese-font mode.
      - New option: `(no)ignorejatype`.
  * Version 0.7  〈2020/01/18〉
      - New options: `(no)bold`, `nojisshape`.
      - New option aliases: `(no)deluxe`.
      - Bug fix.
  * Version 0.6  〈2020/01/12〉
      - New preset: `haranoaji` (thanks: doraTeX).
      - `hiragino` is made an alias for `hiragino-pro`.
  * Version 0.5  〈2019/06/29〉
      - More aliases are provided.
      - The deprecated presets are abolished.
  * Version 0.4  〈2018/05/04〉
      - New presets: `yu-win10`, `sourcehan(-jp)`, `noto(-jp)`, `ume`.
      - New options: `90jis`, `jis2004`.
      - The use of deprecated presets is warned.
  * Version 0.3  〈2015/05/08〉
      - Presets made more alike those of pxchfon.
  * Version 0.2a 〈2013/01/28〉
      - Adjustment for new zxjatype.
  * Version 0.2  〈2009/12/22〉
      - First public version.

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
