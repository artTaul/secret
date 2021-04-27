1. vue创建一个对象 var object = {} 
2. vue 创建一个数组 var arr = []
3. vue 页面引用Util中的方法
export function tableHeaderColor({ row, column, rowIndex, columnIndex }) 
import { tableHeaderColor } from "../../utils/index";
如果在js代码中用可以直接调用方法名即可 如果在<dev>中使用需要在data中定义一个变量 data() {return {tableHeaderColor: tableHeaderColor,}}
