# [jQuery pagination plugin (bootstrap powered)](http://esimakin.github.io/twbs-pagination/)

### Basic usage ###

fork from [twbs-pagination](https://github.com/esimakin/twbs-pagination)

add option ellipsis
add option paginationControl

[demo](http://ashley2014.github.io/twbs-pagination/)

original [doc](http://esimakin.github.io/twbs-pagination/)

```javascript
$('#pagination-demo').twbsPagination({
  totalPages: 35,
  visiblePages: 7,
  ellipsisClass: 'ellipsis',
  ellipsis: '...',
  paginationControl: true
  onPageClick: function (event, page) {
    $('#page-content').text('Page ' + page);
  }
});
```
