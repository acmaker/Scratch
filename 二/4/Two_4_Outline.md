# 飞机起降

## 准备
1.> 背景: Night city with street <br/>

2.> 角色: Airplane


## 001 

## 002 

循环播放: motorcycle passing <br/>

角色: <br/> 
&emsp;&emsp;添加 机场, 大海, 高山 <br/>
&emsp;&emsp;添加 灯光角色使飞机更逼真 <br/>
&emsp;&emsp;添加 1-Glow, 并且添加1, 2, 3 三个造型 用于计时 <br/>
&emsp;&emsp;添加 帆船角色 <br/>



**注意: 使灯光保持面向飞机方向 并且 循环里一直移动到飞机并且面向飞机方向**<br/><br>
**注意: 初始化隐藏, 大小, 左右反转, 向左. <br/>
当接收到to大海信号时避免提前出现就先延时一秒, 然后 <br/>
移至顶层 <br/>
移至坐标相对于大海-10 ( 实现相对运动 )<br/>
显示 <br/>
重复执行到x坐标走到最左边 <br/>
最后在隐藏<br/>**