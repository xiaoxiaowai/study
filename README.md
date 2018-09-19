<h2>JS的数据类型</h2>
<p>1、typeof操作符,不是函数</p>
<p>2、js里面有5种简单的数据类型(Number、Null、Boolean、Undefined、String)和1种复杂的数据类型(Object)</p>
<strong>Undefined</strong>
<p>只有一个undefine值，未经初始化的默认值就是undefined
  var a;<br>
  alert(typeof a); //undefined <br>
  alert(typeof b); //undefined
  </p>
<strong>Null</strong>
<p> 
只有一个null值，是一个空对象指针，所以用typeof操作符检测null是Object。<br>
如果定义的变量将来要保存对象，最好将其初始值设置为null
</p>
<strong>Boolean</strong>
<p>有两个字面值：true、false（区分大小写，TRUE和FALSE不是Boolean值，只是标识符）<br>
</p>
