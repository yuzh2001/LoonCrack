- loon的标准文档里，`response-body-json-replace`方法后面总是`data.level`，一开始我还以为data是个默认的值，代表`根`，但是实际上这个`data`不是默认值。
- 如果默认是个数组，也可以直接`[0].level`，`[1].level`这样来替换。
- 可以直接把一个完整的json对象替换到一个键下，可以参考timestripe.plugin的写法。