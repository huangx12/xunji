#寻机
基于STM32的CCD寻迹小车
主控：STM32F103C8T6
定时器2产生pwm波，定时器3设置为编码器接口模式读取编码器数据，定时器4产生定时中断每10ms计算一次速度，每20ms进行PID运算
目前只接了一个编码器，实现了PID调速，后续还需要调整PID参数，接入另一个编码器，并结合CCD实现寻迹效果。
