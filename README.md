# jquery-bootstrap4-pagination

A JQuery pagination plugin, based on Bootstrap4

## Usage

```html
<div id="pagination"></div>
```

```js
$('#pagination').pagination({
    pageSize: 10,                            // 单页容量
    page: 1,                                 // 当前页
    totalRows: 50,                           // 总条数
    previous: '上一页',                      
    next: '下一页',                          
    debug: false,                           // 调试模式量默false
    onClickPage:                            // 分页按钮回调函数
});
```
