# uukii-time-ago

一个简单的时间转换工具,可以将时间转换为"多久之前"的格式。

## 安装

```bash
npm install uukii-time-ago
```

## ES6方式
## 使用

```typescript
import runtime from 'uukii-time-ago';

const time = new Date();
const result = runtime(time);
console.log(result); // 输出: "刚刚"
```


## CommonJS方式

## 示例

```typescript
const runtime = require('uukii-time-ago');

const time = new Date();
const result = runtime(time);
console.log(result); // 输出: "刚刚"
```
## MIT


这个修改后的版本:

1. 更新了包名为 `uukii-time-ago`。
2. 提供了 CommonJS 和 ES6 两种导入方式的示例。
3. 详细说明了 API 的参数和返回值。
4. 添加了更多的使用示例。
5. 增加了注意事项部分,说明了默认语言和时间范围。

这个 README 文档现在应该能更好地帮助用户理解和使用您的包。如果您还想添加或修改任何内容,请告诉我,我会很乐意继续帮您完善。

