#Jquery Pagination Plugin [V1.2.7.1]
a simple jquery pagination plugin

##Get Started
include the library in the HEAD of your page:
```html
<link href="jquery.pagination.css" rel="stylesheet" />
<script src="jquery-1.11.2.min.js"></script>
<script src="jquery.pagination.min.js"></script>
```

add a element for pagination
```html
<div id="page" class="m-pagination"></div>
```

init pagination
```javascript
$("#page").page({ total: 1000 });
```

##1.2.7 update to 1.2.7.1
* jump input 在IE下 = null
* 分页元素顺序可配置
* css基于bootstrap3, 然后稍做调整排版.
* ajax sync 可配置, 并默认true

###Documentation
[http://mricle.com/JqueryPagination](http://mricle.com/JqueryPagination "JqueryPagination")

###Demo
[http://mricle.com/JqueryPagination/Demo](http://mricle.com/JqueryPagination/Demo "JqueryPaginationDemo")
