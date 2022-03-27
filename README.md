# 工业蒸汽量预测 - zhengqi prediction
 
 
 ## 一、项目背景
 火力发电的基本原理是：燃料在燃烧时加热水生成蒸汽，蒸汽压力推动汽轮机旋转，然后汽轮机带动发电机旋转，产生电能。在这一系列的能量转化中，影响发电效率的核心是锅炉的燃烧效率，即燃料燃烧加热水产生高温高压蒸汽。锅炉的燃烧效率的影响因素很多，包括锅炉的可调参数，如燃烧给量，一二次风，引风，返料风，给水水量；以及锅炉的工况，比如锅炉床温、床压，炉膛温度、压力，过热器的温度等。
 
 ## 二、分析目标
 经脱敏后的锅炉传感器采集的数据（采集频率是分钟级别），根据锅炉的工况，预测产生的蒸汽量。    
 训练数据集：zhengqi_train.csv    
 测试数据集：zhengqi_test.csv 
  
 ## 三、预测方法
 用XGBoost进行回归预测    
 **分析过程详见：zhengqi.ipynb
 
