# resizableBox

## About
htmlの要素をリサイズ可能にするjsプラグインです。
jQueryのインポートが必要です。

## Usage
```html
<body>
  <div class='resizableBox'>
    <p>Resizable</p>
  </div>
  <script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
  <script src="./resizableBox.js" charset="utf-8"></script>
  <script type="text/javascript">
    $('.resizableBox').resizableBox();
  </script>
</body>
```

## Options
| option | default |
|:--|:--:|
| minWidth | 0 |
| minHeight | 0 |
| maxWidth | 10000 |
| maxHeight | 10000 |
| mouseRange | 10 |
| isWidthResize | true |
| isHeightResize | true |

## reference
- http://webnonotes.com/javascript-2/funcresizebox/
