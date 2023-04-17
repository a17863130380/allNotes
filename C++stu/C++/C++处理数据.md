# 3.数据处理
![img.png](图片内容/第三章图片/img.png)
## 3.1简单变量
![img_1.png](图片内容/第三章图片/img_1.png)![img_2.png](图片内容/第三章图片/img_2.png)
### 3.1.1变量名
![img_3.png](图片内容/第三章图片/img_3.png)![img_4.png](图片内容/第三章图片/img_4.png)
> >整型
> ![img_5.png](图片内容/第三章图片/img_5.png)![img_6.png](图片内容/第三章图片/img_6.png)
> 位和字节
> ![img_7.png](图片内容/第三章图片/img_7.png)![img_8.png](图片内容/第三章图片/img_8.png)这里的C++字节指char
> ![img_9.png](图片内容/第三章图片/img_9.png)
> 变量
>![img_10.png](图片内容/第三章图片/img_10.png)
> ![img_11.png](图片内容/第三章图片/img_11.png)
> ![img_12.png](图片内容/第三章图片/img_12.png)大括号初始化，可以试试。
> ![img_13.png](图片内容/第三章图片/img_13.png)
> 无符号整型![img_14.png](图片内容/第三章图片/img_14.png)这是由于存的是二进制补码
> 那么该怎么选择类型呢![img_15.png](图片内容/第三章图片/img_15.png)
> ![img_16.png](图片内容/第三章图片/img_16.png)
> 如果节省内存很重要的时候![img_17.png](图片内容/第三章图片/img_17.png)
> 进制![img_18.png](图片内容/第三章图片/img_18.png)
> ![img_19.png](图片内容/第三章图片/img_19.png)![img_20.png](图片内容/第三章图片/img_20.png)
> 但是进制控制符要在输出前使用对之后的输出才有效。  
> ![img_21.png](图片内容/第三章图片/img_21.png)
> ![img_22.png](图片内容/第三章图片/img_22.png)  
> 后缀![img_23.png](图片内容/第三章图片/img_23.png)
> ![img_24.png](图片内容/第三章图片/img_24.png)
> char型
> ![img_25.png](图片内容/第三章图片/img_25.png)![img_26.png](图片内容/第三章图片/img_26.png)
> ![img_27.png](图片内容/第三章图片/img_27.png)char型实际还是一个整数，通过字符数值编码对应到字符。
> ![img_28.png](图片内容/第三章图片/img_28.png)
> 一些转义序列![img_29.png](图片内容/第三章图片/img_29.png)
> ![img_30.png](图片内容/第三章图片/img_30.png)![img_31.png](图片内容/第三章图片/img_31.png)
> 宽字符类型：  ![img_32.png](图片内容/第三章图片/img_32.png)
> ![img_33.png](图片内容/第三章图片/img_33.png)
> ![img_34.png](图片内容/第三章图片/img_34.png)那些之前大写的TRUE FALSE其实是宏定义
> 
> >const限定符，个人感觉没有define方便，但是书里推荐用const，因为const是可以指定类型的。
> ![img_35.png](图片内容/第三章图片/img_35.png)![img_36.png](图片内容/第三章图片/img_36.png)
> 建议以后还是多用const吧。
整型就这些。
## 浮点数
> 简介：
> ![img_37.png](图片内容/第三章图片/img_37.png)
> >![img_38.png](图片内容/第三章图片/img_38.png)不能有空格要注意。
> ![img_39.png](图片内容/第三章图片/img_39.png)![img_40.png](图片内容/第三章图片/img_40.png)
> 不是~，是减号。印刷错了。注意！！！
> ![img_41.png](图片内容/第三章图片/img_41.png)
> 
> >![img_42.png](图片内容/第三章图片/img_42.png)![img_43.png](图片内容/第三章图片/img_43.png)
> 注意精度不同。![img_44.png](图片内容/第三章图片/img_44.png)
> 浮点常量：![img_45.png](图片内容/第三章图片/img_45.png)
> ![img_46.png](图片内容/第三章图片/img_46.png)![img_47.png](图片内容/第三章图片/img_47.png)
> 这里这个很重要。。。
> ### 符号分类：
> ![img_48.png](图片内容/第三章图片/img_48.png)
> 
> >### 运算符
> ![img_49.png](图片内容/第三章图片/img_49.png)![img_50.png](图片内容/第三章图片/img_50.png)
> 浮点数有效数位数问题需要时刻注意。
> ![img_51.png](图片内容/第三章图片/img_51.png)![img_52.png](图片内容/第三章图片/img_52.png)
> ![img_53.png](图片内容/第三章图片/img_53.png)
> ### 类型转换
> ![img_54.png](图片内容/第三章图片/img_54.png)![img_55.png](图片内容/第三章图片/img_55.png)
> ![img_56.png](图片内容/第三章图片/img_56.png)![img_57.png](图片内容/第三章图片/img_57.png)
> ![img_58.png](图片内容/第三章图片/img_58.png)![img_59.png](图片内容/第三章图片/img_59.png)
> ![img_60.png](图片内容/第三章图片/img_60.png)![img_61.png](图片内容/第三章图片/img_61.png)
> ![img_62.png](图片内容/第三章图片/img_62.png)![img_63.png](图片内容/第三章图片/img_63.png)
> ![img_64.png](图片内容/第三章图片/img_64.png)![img_65.png](图片内容/第三章图片/img_65.png)
> ![img_66.png](图片内容/第三章图片/img_66.png)
