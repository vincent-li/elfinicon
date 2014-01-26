# 基于angularjs seajs raphaeljs jquery 的 svg icon库

elfinicon 是一个动态矢量图标库。

---

## 对名称的解释

一直不知道怎么起名字，原来想叫svg-icon，后来觉得不好，搜搜发现了elfin，意思是小精灵，后来发现挺适合动态icon的，让它像精灵一样

## 类库风格


1. **矢量：有的放矢，无限缩放。**做成矢量的目的是更好的兼容浏览器的缩放，以及其它方式图标产生的锯齿。
1. **动态：动静之间，方寸之外。**静态的图标依然不能展现出浏览的乐趣。使用动态图标不仅乐趣无限还能让用户展开更多的想象。
1. **兼容：上下无界，有容乃大。**使用raphaeljs开源框架操控svg可以做到广泛兼容IE系列。IE无忧，方可安枕。

还有两条适合内部构建组件时考虑：

1. **数据化，加载快，省流量。**把icon做成svg数据，压缩后会大大减小数据量。
1. **异步化，展示快，无延时。**icon数据每个icon一份，根据数据配置异步加载缓存。无需等待大量图标数据下载完成再展示。

## 引用参数解释
- **Jekyll-Bootstrap Framework.** 
- **Jekyll-Bootstrap Framework.** 


## 图标库索引

[icon列表]();

## License
[MIT](http://opensource.org/licenses/MIT)

