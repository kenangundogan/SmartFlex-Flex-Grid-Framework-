# SmartFlex (Flex Grid Framework - Scss/Sass/Css)
Smart grid layouts to get you familiar with building within the "SMART FLEX" grid system.

## Flex Components
- Direction
- Wrap
- Justify Content
- Align Items
- Align Self
- Align Content
- Auto Margin
- Order

## Browser support
- Google Chrome (latest)
- Opera (latest)
- Firefox (latest)
- Safari 6.2+
- Internet Explorer 8+
- iOS 7+
- Android 4.4+
- Windows Phone 8.1+


## Flex Grid, Media Screen Size (-xs-sm-md-lg-xl)

| Media Screen Size  | < 424px          | < 768px         | < 1024px        | < 1279px        | < 1366px        |
| :----------------- |:----------------:|----------------:|----------------:|----------------:|----------------:|
| 100% / 12 * 1      | flex-grid-xs-1        | flex-grid-sm-1       | flex-grid-md-1       | flex-grid-lg-1       | flex-grid-xl-1       |
| 100% / 12 * 2      | flex-grid-xs-2        | flex-grid-sm-2       | flex-grid-md-2       | flex-grid-lg-2       | flex-grid-xl-2       |
| 100% / 12 * 3      | flex-grid-xs-3        | flex-grid-sm-3       | flex-grid-md-3       | flex-grid-lg-3       | flex-grid-xl-3       |
| 100% / 12 * 4      | flex-grid-xs-4        | flex-grid-sm-4       | flex-grid-md-4       | flex-grid-lg-4       | flex-grid-xl-4       |
| 100% / 12 * 5      | flex-grid-xs-5        | flex-grid-sm-5       | flex-grid-md-5       | flex-grid-lg-5       | flex-grid-xl-5       |
| 100% / 12 * 6      | flex-grid-xs-6        | flex-grid-sm-6       | flex-grid-md-6       | flex-grid-lg-6       | flex-grid-xl-6       |
| 100% / 12 * 7      | flex-grid-xs-7        | flex-grid-sm-7       | flex-grid-md-7       | flex-grid-lg-7       | flex-grid-xl-7       |
| 100% / 12 * 8      | flex-grid-xs-8        | flex-grid-sm-8       | flex-grid-md-8       | flex-grid-lg-8       | flex-grid-xl-8       |
| 100% / 12 * 9      | flex-grid-xs-9        | flex-grid-sm-9       | flex-grid-md-9       | flex-grid-lg-9       | flex-grid-xl-9       |
| 100% / 12 * 10     | flex-grid-xs-10       | flex-grid-sm-10      | flex-grid-md-10      | flex-grid-lg-10      | flex-grid-xl-10      |
| 100% / 12 * 11     | flex-grid-xs-11       | flex-grid-sm-11      | flex-grid-md-11      | flex-grid-lg-11      | flex-grid-xl-11      |
| 100% / 12 * 12     | flex-grid-xs-12       | flex-grid-sm-12      | flex-grid-md-12      | flex-grid-lg-12      | flex-grid-xl-12      |


## Flex Container
### flex
```javascript
<div class="flex-row d-flex">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### inline-flex
```javascript
<div class="flex-row d-inline-flex">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```





## Flex Direction
### row
```javascript
<div class="flex-row flex-d-row">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### row-reverse
```javascript
<div class="flex-row flex-d-row-reverse">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### column
```javascript
<div class="flex-row flex-d-column">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### row-reverse
```javascript
<div class="flex-row flex-d-column-reverse">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```




## Flex Wrap
### wrap
```javascript
<div class="flex-row flex-wrap">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### wrap-reverse
```javascript
<div class="flex-row flex-wrap-reverse">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```

### nowrap
```javascript
<div class="flex-row flex-nowrap">
    <div class="flex-item"> <div class="content"> flex item 1</div></div>
    <div class="flex-item"> <div class="content"> flex item 2</div></div>
    <div class="flex-item"> <div class="content"> flex item 3</div></div>
</div>
```