# <h1>Vue.easyUtil</h1>
* <h3>Introduce</h3>
 * <h3>����Vue������������ļ�</h3>
 * <h3>�����ø�����������������������ڿ�������������Ĺ����Բ���������Ҫ���������ļ����������ϸ˵��</h3>
 * <h3>���������ļ�λ��support�ļ����£���л�ṩ������Դ�Ĵ������������Դ���뵽��Ӧ�ĵ�ַ����</h3>
 * <strong>1.selected���������:</strong>�ڸ����������id��text���ԣ��ֱ����������id��Ĭ����ʾ�ı�,</br>
 						&emsp;&emsp;&emsp;&emsp;�����֮����"\<li>\<a class="" val="">text\</a>\</li>"��ǩģ����������������ݼ���</br>
 						&emsp;&emsp;&emsp;&emsp;��������jquery.easyUtil�еĳ�ʼ������������ʹ�ã���ʽ����easyUtil.css���ɡ�</br>
 * <strong>2.j-date�������:</strong>�ڸ����������id��defalulttext���ԣ��ֱ����������id��Ĭ����ʾ�ı�,</br>
 						&emsp;&emsp;&emsp;&emsp;���齨����jquery.jedate�������Ҫ���룬�����䷽����ʼ����ͬʱ��ҪeasyUtil.css��jedate.css��ʽ֧��</br>
* <strong>3.v-outsidecloseָ��:</strong>���е���ⲿ����ط��رղ˵������󣬿�ʹ�ø�������󶨶�Ӧ�Ĺرպ������Ƽ���</br>
* <strong>4.super-table������</strong>���������ʹ���������ԣ�</br>
										&emsp;&emsp;&emsp;&emsp;'maindiv',  //��divid</br>
										&emsp;&emsp;&emsp;&emsp;'bodydiv',  //���bodydivid</br>
										&emsp;&emsp;&emsp;&emsp;'head',   //��ͷid</br>
										&emsp;&emsp;&emsp;&emsp;'body',   //����id</br>
										&emsp;&emsp;&emsp;&emsp;'maindivclass',  //��div class</br>
										&emsp;&emsp;&emsp;&emsp;'bodydivclass',  //���body div class</br>
										&emsp;&emsp;&emsp;&emsp;'loadingpath',   //����ͼ���ַ����Ĭ��ֵ</br>
										&emsp;&emsp;&emsp;&emsp;'iscounter',    //�Ƿ����ü��������ֱ����������id��Ĭ����ʾ�ı�,</br>
										&emsp;&emsp;&emsp;&emsp;�ɿ����Զ����񼰼���ģʽ</br>
 						&emsp;&emsp;&emsp;&emsp;�����֮��������ģ�������Ӧ�ı�����ݼ��ɣ�</br>
 						"\<template slot="thead">\
						\<span class="th" style="width: 25%;">\��ͷ����\</span>\
						\<span class="th" style="width: 20%;">\��ͷ����\</span>\
						\</template>\
						\<template slot="tbody">\
					\<div class="tr" :class="rangClass(i)"  v-for="(data,i) in datas">\
						\<span class="td" style="width: 25%;">\�������\</span>\
						\<span class="td" style="width: 20%;">�������</span>\
					\</div>\
				\</template>\
				\<template>\
					\<div class="easyUtil-noContent" v-show="show">\��������\</div>\
				\</template>\"</br>
 						&emsp;&emsp;&emsp;&emsp;��ʽ������easyUtil.css���ɡ�</br>
* <strong>5.super-page��ҳ���</strong>���������ʹ���������ԣ�</br>
										&emsp;&emsp;&emsp;&emsp;':max="totalPage"',  
										&emsp;&emsp;&emsp;&emsp;'@down="getPageNum"',   
										&emsp;&emsp;&emsp;&emsp;'@up="getPageNum"',   
										&emsp;&emsp;&emsp;&emsp;'@go="getPageNum"',  
								

		

