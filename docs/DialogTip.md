## DialogTip

简单示例

```
const toast = this.$createHrDialogTip({
  txt: '操作成功',
  time: 3000,
})
toast.show()
``` 

Props 配置

参数|说明|类型|默认值
--|:--:|--:|--:
txt| 文字| String| ""
type| tip类型(succ/loading)| String| "succ"
time| 展示时间| Number| 1800
maskClick| 是否可以点击遮盖| Boolean| false
maskType| 遮盖层样式| String| 'fff'

