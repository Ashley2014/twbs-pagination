# [jQuery pagination plugin (bootstrap powered)](http://esimakin.github.io/twbs-pagination/)

### Basic usage ###

fork from [twbs-pagination](https://github.com/esimakin/twbs-pagination)

add option ellipsis

original [doc](http://esimakin.github.io/twbs-pagination/)

```javascript
$('#pagination-demo').twbsPagination({
  totalPages: 35,
  visiblePages: 7,
  ellipsisClass: 'ellipsis',
  ellipsis: '...'
  onPageClick: function (event, page) {
    $('#page-content').text('Page ' + page);
  }
});
```
