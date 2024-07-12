#  ソフトウェア工房 Webプロジェクト
---
> ### ディレクトリ構成
---
`/`：ディレクトリ区切り `.`：カレントディレクトリ `#`：コメントアウト
```directory
ROOT
  .README.md
  /html  #HTMLディレクトリ
    .html_files
  /assets
    /css #CSSディレクトリ
      .ccs_files
      /bin #参照用CSSディレクトリ
        .min.css_files
    /scss #SCSSディレクトリ
      .scss_files
    /js #JavaScriptディレクトリ
      .js_files
    /fonts #フォント用CSSディレクトリ
      .fonts.css_files
```
---
> ### コーディングについて
---
- **開発環境**
  - VisualStudioCode
  - 拡張機能
    - Live Sass Compiler
    - Live Server
- **CSSについて**
  - htmlでは`min.css`を参照しています。
  - SCSSを採用しています。
- **JSについて**
  - 機能ごとにファイルを分けています。
---
