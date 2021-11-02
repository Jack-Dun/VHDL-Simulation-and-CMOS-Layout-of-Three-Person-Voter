# VHDL-Simulation-and-CMOS-Layout-of-Three-Person-Voting-Device
本设计三人表决器，是代表投票或举手表决的表决装置，为本人的课程设计。表决时，与会的有关人员只需按下各自表决器上赞成、反对或弃权的某一按钮，荧光屏上即显示出表决结果。在三人表决器中，三个人分别用手指拨动开关SW1、SW2、SW3 来表示自己的意愿，如果对某决议同意，各人就把自己的指拨开关拨到高电平（上方），不同意就把自己的指拨开关拨到低电平（下方）。表决结果用（高电平）显示，如果决议通过那么实验板上L2亮；如果不通过那么实验板上L1亮；如果对某个决议有任意二到三人同意，那么此决议通过，L2亮；如果对某个决议只有一个人或没人同意，那么此决议不通过，L1亮。
<!-- more -->
# VHDL-Simulation-and-CMOS-Layout-of-Three-Person-Voting-Device
# 三人表决器的VHDL设计仿真与CMOS版图设计
1. 独立完成集成电路的设计过程；
2. 对电路进行仿真验证；
3. 根据所用的工艺，选取合理的模型库；
4. 选用以lambda为单位的设计规则；
5. 全手工、层次化设计版图；
6. 达到指导书提出的设计指标要求；
7. 用VHDL进行电路的前期功能设计与仿真；
8. 用CMOS设计出合理且切实可行的逻辑电路；
9. 进行版图绘制，并进行检测。
# CMOS版图
![](https://raw.githubusercontent.com/Jack-Dun/VHDL-Simulation-and-CMOS-Layout-of-Three-Person-Voting-Device/main/%E4%B8%89%E4%BA%BA%E8%A1%A8%E5%86%B3%E5%99%A8L-Edit%E7%89%88%E5%9B%BE%E9%A2%84%E8%A7%88.png")
