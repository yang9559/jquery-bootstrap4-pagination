# jquery-bootstrap4-pagination

A JQuery pagination plugin, based on Bootstrap4

## Usage

```html
<div id="pagination"></div>
```

```js
$('#pagination').pagination({
    pageSize: 10,                            // 一页数据的数量默认5个
    page: 1,                                 // 当前第几页默认第1页
    totalRows: 50,                           // 数据总条数默认10条
    pageLength: 10,                          // 最多显示分页按钮数量默认5个
    previous: '上一页',                      // 上一页按钮显示名称量默上一页
    next: '下一页',                          // 下一页按钮显示名称量默下一页
    debug: false,                           // 调试模式量默false
    onClickPage: function(this, num) {}     // 点击回掉函数量默null
});
```
