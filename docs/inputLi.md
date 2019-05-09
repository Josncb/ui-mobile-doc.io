## hr-input-li

简单示例
```
<hr-input-li>
  <div class="px14" slot="lable">单项输入</div>
  <cube-input v-model="value" :borderHas='false' ></cube-input>   
</hr-input-li>

```  
Props 配置

参数|说明|类型|可选值|默认值
--|:--:|--:|--:|--:
value| input 的value| Any| -| ""

slot 配置

参数|说明|
--|:--:|
lable| li的name|
icon| li后的icon|