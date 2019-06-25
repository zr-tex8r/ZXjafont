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

  - TeX format: XeLaTeX.
  - Prerequisite packages: fontspec.

### INSTALLATION

Move the files as follows (in a system compliant to TDS 1.1):

  - `*.sty`   → $TEXMF/tex/xelatex/zxjafont/

And rehash your TEXMF trees if necessary.

### LICENSE

This package is distributed under the MIT License.

Revision History
----------------

  * Version 0.5  〈2019/06/29〉
      - More aliases are provided.
      - The deprecated presets are abolished.
  * Version 0.4  〈2018/05/04〉
      - New preets: `yu-win10`, `sourcehan(-jp)`, `noto(-jp)`, `ume`.
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
http://zrbabbler.sp.land.to/
