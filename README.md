# Embedded
Embedded Homework

实验一：根据小熊派 IoT 实验板电路（见资料目录），通过 STM32 CubeMX 构建控制 LED灯的工程，在 MDK下编译和仿真。要求实现以下三种显示模式：
1、常亮；2、闪烁（比如：亮 1s 灭 1s）；3、呼吸灯模式（慢慢从灭到最亮，再从最亮慢慢回到灭的过程，1 分钟重复此过程 10次）。
实验过程可以参见：https://blog.csdn.net/as480133937/article/details/98947162


实验二：根据小熊派 IoT 实验板电路（见资料目录），通过 STM32 CubeMX 构建控制两个按键的工程，
按键使用外部中断方式实现，在 MDK下编译和仿真。要求实现选择实验一中的三种显示模式的轮换选择。
实验过程可以参见：https://blog.csdn.net/as480133937/article/details/98983268


实验三：根据 volatile 修饰符的特性，构造一个程序（主程序、中断子程序的程序结构）。要求：无 volatile 时，程序会出现随机的运行逻辑错误。
加入 volatile 后，程序随机的运行逻辑错误消失。
参见：https://blog.csdn.net/weixin_44363885/article/details/92838607


实验四-用 C语言和MDK编译器研究 ARM 的内存变量的大(小)尾存储方式和字节对齐方式，理解CPU 和编译器为何如此处理。
参见：1、C/C++内存对齐详解：https://zhuanlan.zhihu.com/p/30007037
2、内存对齐总结：https://www.cnblogs.com/iQXQZX/p/14049734.html


实验五：使用小熊派 IoT实验套件和STM32CubeMX，基于定时器2，实现 20KHz 定时中断，由此20KHz生成 100Hz的 PWM周期信号，产生占空比慢慢增加和
慢慢减小的PWM信号，获得 LED的呼吸灯效果（每分钟呼吸 10次）。用逻辑分析仪测量此信号的图形，自己编程用小熊派测量此信号的周期和高电平脉冲的周期变化。
参见：1、https://blog.csdn.net/as480133937/article/details/99201209
2、https://blog.csdn.net/as480133937/article/details/99231677
3、https://blog.csdn.net/as480133937/article/details/99407485


实验六：使用小熊派 IoT实验套件和STM32CubeMX，用逻辑分析仪分析和比较 Uart 、I2C 和 SPI 传输同样数据的通讯时序。
1、逻辑分析仪资料：见本课程资料库中的逻辑分析仪子文件夹。
2、分析结果用  saleae logic 软件采集的时序图。


实验七：使用小熊派 IoT实验套件和STM32CubeMX，根据 IoT的开发资料，编写在 LCD 上显示字符（包含汉字），和简单几何图形的 LCD 驱动库。
并在此驱动库基础上，给出几个显示样例。
1、LCD 驱动控制芯片资料见本课程资料库中的"小熊派IoT开发板"子文件夹。
2、参考 LCD 样例代码见本课程资料库中的"小熊派IoT开发板"子文件夹中。

部分演示视频。
