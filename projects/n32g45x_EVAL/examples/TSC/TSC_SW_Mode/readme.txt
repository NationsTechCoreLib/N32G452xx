1、功能说明
    1、轮询三个触摸按键K5、K6，有按键输入时LED闪烁

2、使用环境

    软件开发环境：KEIL MDK-ARM V5.26
    硬件环境：基于全功能板N32G457QEL-EVB开发

3、使用说明
    
    系统配置；
        1、时钟源：HSE+PLL
        2、系统时钟：16MHz
        3、TSC端口： PC6:CH8        PC7:CH9
        4、LED控制端口：PB10
        5、UART端口：PA9（115200，8bit data，1bit stop）

    使用方法：
        1、在KEIL下编译后烧录到全功能板，通电，有触摸按键时，通过LED闪烁指示按键状态
           K5:闪烁一次
           K6:闪烁两次
        2、全程可通过串口工具查看相关信息
        
4、注意事项
    J41、J42、J43必须断开。