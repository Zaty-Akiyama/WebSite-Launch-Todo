# OGPについて
基本的に1.91:1の画像を用意すれば問題ない

## HEAD内に記載する内容

```
<meta property="og:title" content="表示するサイトのタイトル" />
<meta property="og:type" content="website" />
<meta property="og:url" content="表示するページのURL" />
<meta property="og:image" content="画像のpath" />
<meta property="og:description" content="表示するページの説明文" />
<meta property="og:site_name" content='サイトの名前' />

<meta name="twitter:site" content="TwitterのID(@あり)" />
<meta name="twitter:title" content="表示するサイトのタイトル" />
<meta name="twitter:description" content="表示するページの説明文" />
<meta name="twitter:image" content="画像のpath" />
<meta name="twitter:card" content="summary_large_image" />
```

## Twitter

twitter:cardがsummary_large_imageのとき（大きい画像を表示するカード）は画像サイズは以下の通り

| アスペクト比 | 最小サイズ | 最大容量 |
|----|----|----|
| 1.91:1 | 600 × 314px | 5MB |

## LINE

LINEはアスペクト比1.8:1に程度にトリミングされる
