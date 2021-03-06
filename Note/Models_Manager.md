Models-Manager管理类  
====

## 介  绍：  
1、咱们Django的Models模块就是和数据库打交道的模块  
2、通过自己定义Models，就不用写sql语句去操作数据了，且一劳永逸  

## 说  明：
1、直接复制粘贴能用的Models代码已经在[第一页](https://github.com/KissMyLady/Django/blob/master/Note/Models_deep_sty.md)贴出来了  
2、这里我将详细说明，是如何通过升级，达到第一页的代码  

## 管理器升级：
### 原代码  
![1](https://github.com/KissMyLady/Django/blob/master/Img/m-1.jpg)  

### 一阶段--原始  
![2](https://github.com/KissMyLady/Django/blob/master/Img/m-2.jpg)  

### 二阶段--指定义类属性   
![3](https://github.com/KissMyLady/Django/blob/master/Img/m-3.jpg)  

### 三阶段--自定义all方法    
![4](https://github.com/KissMyLady/Django/blob/master/Img/m-4.jpg)  

### 四阶段--BookInfo增添功能  
![5](https://github.com/KissMyLady/Django/blob/master/Img/m-5.jpg)

### 五阶段--将功能封装入Manager  
![6](https://github.com/KissMyLady/Django/blob/master/Img/m-6.jpg)  

### 六阶段--解耦类名  
![7](https://github.com/KissMyLady/Django/blob/master/Img/m-7.jpg)  


## 接下来  
- [Django主页](https://github.com/KissMyLady/Django)  
- [Models-M深入介绍](https://github.com/KissMyLady/Django/blob/master/Note/Models_deep_sty.md) 
- [Models-数据库设置](https://github.com/KissMyLady/Django/blob/master/Note/Models_mysql.md)  

