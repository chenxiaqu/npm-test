# web-components自定义组件-test
目前正在学习web-components，项目中的实现就不发出来了，发布一些自己实现的小demo。

- 以vue项目为例

如何引入？在我们的main.js文件中按需引入
```
import { Ploading } from 'p-web-cmp'; // 按需引入组件
Ploading(); // 执行创建组件元素 
```
如何使用？在相应vue页面正常编写标签即可
```
<p-loading :visible="pLoadingVisible" :color="loadingColor"></p-loading>
```

目前只有一个简单的loading组件，显隐控制，loading颜色。后续会加入更多的组件！！！
### 如果有相关的交流群，请留言~感谢~

