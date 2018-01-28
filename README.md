# vue_tables_xlsx_demo

### 官方地址
* vue-data-tables:  
https://njleonzhang.github.io/vue-data-tables/#/event?id=filtered-data
* js-xlsx:  
https://github.com/sheetjs/js-xlsx

### 3个例子
1. 导出.xlsx（vue-data-tables结合js-xlsx实现导出.xlsx文件）
1. writexlsx（官方例子改造：https://github.com/SheetJS/js-xlsx/tree/master/demos/vue）</router-link><br/>
1. 导出.csv（官方例子：https://njleonzhang.github.io/vue-data-tables/#/event?id=filtered-data）

### 兼容性问题：
1. 在Safari 10.0版本中，有报错：`Failed to load resource: Frame load interrupted`，原因是safari还不支持，升级到10.1以上即可支持。详见：https://github.com/eligrey/FileSaver.js/issues/215  

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
