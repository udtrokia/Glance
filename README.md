# Gun 源码注解
本项目是注释版的 Gun 源码，原始代码来自: https://github.com/amark/gun。

Mercury, 2018-4-28

## 附录：各个源码文件的作用简介

### gun.js
+ 环境处理
+ 通用函数(USE)
  + 导入入其他函数库接口制作
  + 导出 gunjs 接口制作
  + !失忆机器实验，状态机管理
  + !存储数据预处理
  + 数据入库
  + 优化数据传递速度
  + 数据检查机制
  + 回传数据，请求部分
  + 数据失效及消除
  + !!链式管理(接入多个文件
  + 链类型处理
  + 同步优化
  + 打包 GUN
  + 服务器回传数据
  + 客户端存储数据
  + 客户端数据加密处理
  + 网络部分

# GUN
Hello wonderful person! :) Thanks for using GUN, feel free to ask for help on https://gitter.im/amark/gun and ask StackOverflow questions tagged with 'gun'!

```javascript
{ [Function: Gun]
  is: [Function],
  version: 0.9,
  chain: 
   Gun {
     toJSON: [Function],
     opt: [Function],
     back: [Function],
     chain: [Function],
     get: [Function],
     put: [Function],
     on: [Function],
     val: [Function],
     once: [Function],
     off: [Function],
     map: [Function],
     set: [Function] },
  fn: { is: [Function: is] },
  fns: { is: [Function: is] },
  bi: { is: [Function: is] },
  num: { is: [Function: is] },
  text: 
   { is: [Function: is],
     ify: [Function],
     random: [Function],
     match: [Function] },
  list: 
   { is: [Function: is],
     slit: [Function: slice],
     sort: [Function],
     map: [Function],
     index: 1 },
  obj: 
   { is: [Function: is],
     put: [Function],
     has: { [Function] _: '.' },
     del: [Function],
     as: [Function],
     ify: [Function],
     to: [Function],
     copy: [Function],
     empty: [Function],
     map: [Function] },
  time: { is: [Function] },
  HAM: [Function: HAM],
  val: 
   { is: [Function],
     rel: { _: '#', is: [Function], ify: [Function] } },
  node: 
   { _: '_',
     soul: { [Function] ify: [Function], _: '#' },
     is: [Function],
     ify: [Function] },
  state: 
   { [Function: State]
     _: '>',
     drift: 0,
     is: [Function],
     lex: [Function],
     ify: [Function],
     to: [Function],
     map: [Function] },
  graph: 
   { is: [Function],
     ify: [Function],
     node: [Function],
     to: [Function] },
  on: 
   { [Function: onto]
     put: [Function],
     get: [Function],
     _: { next: [Function: next] },
     off: [Function] },
  ask: [Function: ask],
  dup: [Function: Dup],
  create: [Function],
  log: { [Function] once: { [Function] welcome: 1 } },
  Mesh: { [Function: Mesh] hash: [Function] },
  tag: { opt: { tag: 'opt', to: [Object], last: [Object] } } }
```
