# 西电机器人暑假训练营
为了招募西电Roobmaster的新赛季队员，我们在暑假以夏令营的形式进行为期3周的培训，Summer Camp的本质依然是机器人比赛，某种意义上，这在未来会发展成校内赛。

## Summer Camp 招募
我们有机械、嵌入式、算法、项目管理，4个方向供选择。最终招募了60名大一同学加入Summer Camp。他们的专业可以给以后希望加入我们的同学提供参考：
- 管理科学与工程类
- 工业设计
- 电气工程及其自动化
- 电子封装技术
- 生物技术
- 通信工程专业
- 电子信息工程
- 微电子科学与工程
- 应用数学
- 探测制导与控制技术
- 软件工程
- 计算机科学与技术
- 遥感科学与技术
- 电磁场与无线技术
- 机械设计制造及自动化
- 测控技术与仪器
- 信息工程
- 集成电路设计与集成系统
- 智能科学与技术
- 信息对抗技术
- 电子科学与技术

事实上，机器人技术是一项综合技术，无论来自什么专业都可以在我们的团队找到属于自己的位置。

## Summer Camp 培训
第一周是技术培训，包括Solidworks的使用、stm32的使用、linux操作系统的使用、git代码托管、以及一些机器人学。Summer Camp的成员需要掌握高数上下两册、线性代数、C语言、以及大一的其他课才能听懂我们的培训。事实上，刚学完线性代数的他们，消化一些公式的推导还是有些困难。

## Summer Camp 比赛
每10人随机分成一组，机械/嵌入式/算法/项目管理的比例是3：3：3：1，每个队伍会获得一辆基础款机器人以及1500元的备赛额度。

基础款机器人包括:
- 4个电机
- 4个麦克纳姆轮
- 带有4个独立悬挂的机器人底盘
- 一块专为Summer Camp设计的stm32f4主控板，带有板载IMU（DJI板我们是用不起的）
- 一块树莓派

比赛场地是一个长8米宽5米的迷宫，由20厘米高的木板作为围墙搭建。每个队伍要自主设计机器人，进入迷宫、抓取魔方、走出迷宫，根据用时长短排名。如果机器人没有成功抓取魔方，走出迷宫的用时会加5分钟；迷宫中一共有4个魔方，只有1个是六面拼好的，如果抓取到六面拼好的魔方，总用时就会减去5分钟作为奖励，而抓取到普通的魔方，用时不增不减。

## Summer Camp 备赛
成员由2周的时间准备，最后一天提交技术报告并比赛。基础款机器人是为了加速他们的研发进度，其他物料、工具、传感器都需要现买，我们只提供1500元的额度。不过我们为6个组准备了4台3D打印机和一台数控，具备基本的机械加工能力。

## Summer Camp 挑战
### 机械
每个组的机械成员需要设计抓取魔方的机械臂，我们提供的基础款机器人是4轮独立悬挂，但只有夏令营1组和我们XDU Robomaster自己的队伍改进了底盘设计。

### 嵌入式
每个组的嵌入式成员要负责整车的硬件以及代码逻辑，我们提供了基础的代码帮助他们实现基础控制，也就是说每个组领到的车本身就已经能动能跑，但是要从迷宫避障，甚至还要走直线等，还需要很多工作，比如PID控制算法。

### 算法
每个组的算法成员要编写视觉识别并运行在树莓派上，需要识别魔方以及六面拼好的魔方以及迷宫中的一些用来当作路标的二维码，然后解算机械臂需要移动的位置或机器人需要移动的姿态，然后通过串口发送给单片机。

### 项目管理
花好1500块钱、做好财务、管好两周的进度、协调10个人的合作、组织成员撰写技术报告、做好文档资料以及物料的整理、积极担任Leader的角色并且以开进度会等形式、帮助团队完成任务，自己也会承担一部分研发任务，但更多的是扮演一个push man（推着所有人往前走的人）。

## 总结
通过这次Summer Camp，我们挖掘了很多了未来的XDU Robomaster的队员，也培养了很多曾经是技术小白但如今愿意成为XDU Robomaster的人，这个夏令营将Robomaster一年的备赛体验浓缩到两三周，融合了所有的RM备赛元素。如果可能，我们将每年进行这样的投入，招募XDU Robomaster队员。
