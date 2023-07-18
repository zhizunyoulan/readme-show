# water.js  ![](https://img.shields.io/badge/license-MIT-blue) ![](https://img.shields.io/badge/npm-v1.0.1-blue) ![](https://img.shields.io/badge/circleci-passing-brightgreen) 
[![](https://img.shields.io/badge/English-en-blue)](README-en.md)

![](https://github.com/penghuwan/water.js/blob/master/logo.png)

water.js是一个如何编写一个好玩的readMe的示范例子，它具有以下特点
+ 正式性： 一看就知道这个库是认真写的
+ 优雅性： 给人以美好的视觉感受，和其他黑白两色的readMe区分开来
+ 装笔性：  有利于向他人展示自己代码的美好的一面

## Installation
```
npm install water-js
```
## Examples
```js
const { water } = require('water-js')

function print() {
  const content = water(true);
  console.log(content);
}
```
output
```
// 输出
我就是来水的
```
$$
\begin{Bmatrix}
   a & b \\
   c & d
\end{Bmatrix}
$$
$$
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
$$


```mermaid
graph LR
A[方形] -->B(圆角)
    B --> C{条件a}
    C -->|a=1| D[结果1]
    C -->|a=2| E[结果2]
    F[横向流程图]
```




## License
Water.js is MIT licensed.
