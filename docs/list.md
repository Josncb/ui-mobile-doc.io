## hr-list

简单示例

```
<hr-list>
  <hr-li :list='hrlist' @click='clickHandler'></hr-li>
</hr-list>
```

list 只做内容分发 是列表盒子样式
``` 
  margin-top: 20px;
  background: #fff;
  padding-left: 20px;

```

## hr-li

简单示例

```
<hr-list>
  <hr-li :list='hrlist' @click='clickHandler'></hr-li>
</hr-list>
```

Props 配置

参数|说明|类型|可选值|默认值
--|:--:|--:|--:|--:
list| 要渲染的li数组|Array| -| []

list 子配置项

参数|说明|类型|可选值|默认值
--|:--:|--:|--:|--:
icon| 列表前的icon| String| -| ""
name| 列表的name| String| -| ""
xinghao| 列表前的星号| Boolean| true/false| false
state| 列表值的状态| Any| -| ""
news| 列表是否为新增| Boolean| true/false| false

事件
参数|说明|参数
--|:--:|--:
click| 用户点击li| 无