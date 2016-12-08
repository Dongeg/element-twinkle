# ios-form-twinkle
iso表单获取焦点时闪一下问题
```css
.ly_item input {
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);/*关键代码*/
    -webkit-appearance:none;
    width:100%;
    height: 2em;
    line-height: 2em;
    border: none;
    padding: 0;
    outline: none;
    font-size: 1em;
}
```
