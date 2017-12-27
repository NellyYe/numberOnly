# numberOnly

# vue组件
## 使用方法，main.js注册之后进行使用，充当组件使用

```
import { vueNumberOnly } from "@/directives/number-only.js"; // 数字 位数
Vue.use(vueNumberOnly);
```


## v-number-only:10.abs="2"
1.abs去除负数

2.:后面是整数最多的位数 2表示小数位数
