# 概要
CDNやnpmを使用しないで、Element Uiを導入する方法

# 必要な記述
```html
<!-- head に記述する-->
<link rel="stylesheet" href="element_ui/lib/theme-chalk/index.css" />

<!--bodyタグの下に記述する -->
<script src="element_ui/lib/index.js"></script>
<script src="./element_ui/lib/umd/locale/ja.js"></script>
```

# ディレクトリー構成
使用するディレクトリーとファイルのみ記載

<font color="Red">※ 記載していないディレクトリーやファイルは、必ず消さずに残しておく</font>
```
.
├── element_ui/
│   └── lib/
│       ├── theme-chalk/
│       │   └── index.css
│       ├── umd/
│       │   └── locale/
│       │       └── ja.js
│       └── index.js
├── .gitignore
├── index.html
└── README.md
```

# 参考資料
- [[公式]Element Ui](https://element.eleme.io/)
- [[公式]ElementUI/lib](https://github.com/ElementUI/lib)
