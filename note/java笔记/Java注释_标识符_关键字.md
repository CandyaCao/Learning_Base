# 第二章
## 注释
	用来给程序员看的，对JVM是不可视,
	增加代码可读性。
		单行注释：//
				注释一行的内容
				变量，}结束的地方使用单行注释
		多行注释：/*
				  *对多行做解释
				  *对package、class、方法和算法的描述用多行注释
				  */
					
		文档注释：用来生成API文档
				  /**
				  *类上面，方法上面，常量的标注
				  */
				  javadoc -author -version -d doc *.java

## 代码格式
* 一行代码结束，加;
* 所有代码都要放在{}
* 代码加空格，增加可读性

## 标识符
* 标识符是类名，方法名，变量名
* 标识符的合法性：
		必须以字母，_ $开头，不能以数字开头
		由字母,数字,_ $组成
		区分大小写
		标识符用有意义的单词
		不能用Java关键字
		没有长度限制
## 关键字
## 基本数据类型
	数据类型的意义：用来决定该数据在内存空间开辟多大空间保存
		在定义变量的时候就需要先声明数据类型,数据类型 变量名=变量值;
	数据类型的分类：
		基本数据类型：
			整数类型 byte short int long   
				** 默认数据类型是int **
				定义long类型数据，后面加l或L
			浮点类型 float double
				** 默认为double **
				定义float类型数据，后面加f或F
			布尔类型 boolean
			字符类型 char
		引用数据类型：
			类类型：class定义
			接口类型：interface定义
			数组类型：[]定义
	基本数据类型
		boolean:在java中只有true,false  一般用在判断语句中
		char：定义字符用'',保存无符号的16位的整数 
			eg:char c1 = '中'；
			   char c2 = 'a';
			   char c3 = 97;
			   char c4 = "\u0060";
			   char c5 = 0x0060;
		String类型：字符串类型不是基本数据类型，是类类型
				字符串的值用""引起来
	数据类型转换：
		强制类型转换：将高精度的数据给低精度的数据就需要强制类型转换（从后往前截取）
			bype<short<int<long<float<doble
		隐式数据类型转换：将低精度的数据给高精度的数据是隐式数据转换（从前往后补齐）

## 变量声明、赋值、初始化
	变量声明：int a;
	变量赋值：a=10;
	变量初始化：int a=10;
	数据类型 变量名 = 变量值;
	变量先声明后赋值，再使用

## 推荐的命令规则-------驼峰规则
	类名和接口名都是每个单词首字母大写
	方法名和变量名都是从第二个单词首字母大写
	常量所有单词都大写，由final修饰
	

