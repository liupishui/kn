# kn  
##js  
### js获取transform值
```javascript
   $(this)[0].style.transform = 'translateY('+ ($(this).css('transform').match(/([-]\d+)|(\d+)/g)[5]-15) +'px)';
```
