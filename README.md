
graph TD
A1[需求输入] --> |性能需求/约束条件| B1(参数范围确定)
B1 --> C1[槽极配合优化]
B1 --> D1[定转子拓扑优化]
B1 --> E1[绕组结构选型]
C1 & D1 & E1 --> F1[多目标优化模型]
F1 --> G1{粒子群算法优化}
G1 --> H1[拓扑方案组合]
H1 --> I1[有限元分析对比]
I1 --> J1((选定初始拓扑方案))
