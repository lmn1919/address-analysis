### 复制地址自动识别

#### 1.安装

```
npm install address-analysis
```

#### 2.使用

```js
//CommonJS
let { getAddress } =require('address-analysis')
//ES6
import { getAddress } from 'address-analysis'

console.log(getAddress('广东省广州市番禺区大石街道会江村110号，刘发福'))

{address : "会江村110号",
 city : "广州市",
 cityCode : "4401",
 county : "番禺区",
 countyCode :"440113",
 name : "刘发福",
 province : "广东省",
 provinceCode : "44",
 street : "大石街道",
 streetCode : "440113012"}
```