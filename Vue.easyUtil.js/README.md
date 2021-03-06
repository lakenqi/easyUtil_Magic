# <h1>Vue.easyUtil</h1>
* <h3>Introduce</h3>
 * <h3>基于Vue的组件生成器文件</h3>
 * <h3>可利用该生成器生成如下组件，便于开发，样式需引入easyUtil_basic.css和easyUtil_component.css,如果使用下拉框则引入easyUtil_selected.css可在vueDemo文件夹下找到</h3>
 <h3>部分组件的功能性操作可能需要依赖其他文件，请参阅详细说明</h3>
 * <h3>所有依赖文件位于support文件加下，感谢提供依赖资源的大神，如需更多资源，请到相应的地址下载</h3>
 * <strong>1.easy-selected  下拉框组件:</br>
 &emsp;&emsp;&emsp;&emsp;</strong>在父级组件上用id，display v-model="display" @val="自定义方法名" :values="自定义名称"属性：</br>
 						&emsp;&emsp;&emsp;&emsp;分别命名组件的id，默认显示文本，选中的值和下拉框内容,</br>
 						&emsp;&emsp;&emsp;&emsp;样式引入easyUtil.basic和selectd即可。初始化时，设置display默认显示的值，values下拉框值和@val获得选中值的方法即可</br>
 * <strong>2.j-date  日期组件:</br>
 &emsp;&emsp;&emsp;&emsp;</strong>在父级组件上用id，defalulttext属性，分别命名组件的id和默认显示文本,</br>
 						&emsp;&emsp;&emsp;&emsp;本组建基于jquery.jedate插件，需要引入，并用其方法初始化，同时需要easyUtil.css及jedate.css样式支持</br>
* <strong>3.v-outsideclose指令:</br>
&emsp;&emsp;&emsp;&emsp;</strong>如有点击外部任意地方关闭菜单的需求，可使用该组件，绑定对应的关闭函数名称即可</br>
* <strong>4.super-table  表格组件:</br>
&emsp;&emsp;&emsp;&emsp;</strong>父级组件上使用如下属性：也可参考demo文件使用</br>
										&emsp;&emsp;&emsp;&emsp;'mainid',  //主divid</br>
										&emsp;&emsp;&emsp;&emsp;'bodyid',  //表格bodydivid</br>
										&emsp;&emsp;&emsp;&emsp;'theadid',   //表头id</br>
										&emsp;&emsp;&emsp;&emsp;'tbodyid',   //表身id</br>
										&emsp;&emsp;&emsp;&emsp;'emptyflag',   //显示无值内容标识</br>
										&emsp;&emsp;&emsp;&emsp;'mainclass',  //主div class，选填</br>
										&emsp;&emsp;&emsp;&emsp;'bodyclass',  //表格body div class，选填</br>
										&emsp;&emsp;&emsp;&emsp;'loadingpath',   //加载图表地址，有默认值，选填</br>
										&emsp;&emsp;&emsp;&emsp;'iscounter',    //是否启用计数器，分别命名组件的id和默认显示文本,可开启自定义表格及计数模式，选填</br>
										&emsp;&emsp;&emsp;&emsp;'emptytip',   //无值提示内容，有默认值，选填</br>
										&emsp;&emsp;&emsp;&emsp;'emptyflag',   //无值判断标识，必填</br>
* <strong>5.super-page  分页组件:上下翻页，回车或鼠标离开跳转自定义页码:</br>
&emsp;&emsp;&emsp;&emsp;</strong>父级组件上使用如下属性：也可参考demo文件使用</br>
										&emsp;&emsp;&emsp;&emsp;'v-model="value"',  </br>
										&emsp;&emsp;&emsp;&emsp;'show=1',  </br>
										&emsp;&emsp;&emsp;&emsp;':nums="totalNums"', </br> 
										&emsp;&emsp;&emsp;&emsp;':max="totalPage"', </br> 
										&emsp;&emsp;&emsp;&emsp;'@down="getPageNum"', </br>  
										&emsp;&emsp;&emsp;&emsp;'@up="getPageNum"', </br>  
										&emsp;&emsp;&emsp;&emsp;'@go="getPageNum"', </br>
* <strong>6.super-bar  div生成横向bar图带数字:</br>
&emsp;&emsp;&emsp;&emsp;</strong>父级组件上使用如下属性：</br>
							&emsp;&emsp;&emsp;&emsp;'bar=""', 柱图宽度  </br>
							&emsp;&emsp;&emsp;&emsp;'value=""', 对应的值 </br>  
* <strong>7.super-progressbar  进度条 带名称 数字跟随 显示百分比:</br>
&emsp;&emsp;&emsp;&emsp;</strong>父级组件上使用如下属性：</br>
							&emsp;&emsp;&emsp;&emsp;'name=""', 名称  </br>
							&emsp;&emsp;&emsp;&emsp;'value=""', 对应的值</br>
							&emsp;&emsp;&emsp;&emsp;'color=""', 对应的颜色 </br>	
							&emsp;&emsp;&emsp;&emsp;'percent=""', 对应的百分比 </br>
							&emsp;&emsp;&emsp;&emsp;'is-percent=""', 是否显示百分比，默认true </br>
* <strong>8.to-top  返回顶部按钮组件，点击可返回页面顶部；页面滚动自动显示，返回顶部自动隐藏:</br>
&emsp;&emsp;&emsp;&emsp;</strong>父级组件上使用如下属性：</br>
							&emsp;&emsp;&emsp;&emsp;'id=""', 按钮id  </br>
							&emsp;&emsp;&emsp;&emsp;'title="返回顶部"', 对应的title属性值，默认为“返回顶部”</br>
							&emsp;&emsp;&emsp;&emsp;'text="︿"', 按钮显示的内容，默认是向上箭头 </br>	
							&emsp;&emsp;&emsp;&emsp;可以自定义class样式 </br>									

		

