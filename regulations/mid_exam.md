---
title: 中期考核内容、考核标准
description: 不会啊，怎么办
published: true
date: 2022-11-15T17:01:13.710Z
tags: 
editor: markdown
dateCreated: 2022-11-15T06:49:33.720Z
---

# 考试要求
## 你可以
1. 现场查阅各种资料，包括 Bilibili 视频教程、科服 Wiki、本考试标准和要求
2. 考前请求其他队员辅导
3. 在无原则性错误的前提下申请无限次补考
4. 特殊情况滴滴监考或队长

### 你不可以
1. 现场拷问其他队员，或携带其他同学作为参考资料
2. 违规操作，导致硬件损坏或数据丢失
### 你应该
1. 注意维护测试用设备，注意螺丝刀等工具的使用规范，尤其不能滑牙
2. 在监考员认为不可以的时候听从他/她

## 监考员可以
1. 针对队员*明显没有发现的*错误操作进行一个指的出，并在小本本上记一笔
2. 提示考纲外的部分知识
3. 鼓励参评队员

### 监考员不可以
1. 提示考纲内的操作知识
2. 接受参评队员的投喂
3. 嘲讽参评队员

### 监考员需要对三个科目分别准备
1. 对于科目一，预先将sm961、860evo安装回机器中，并连接好线缆，删除两块硬盘的分区以备装机  
2. 对于科目二，预先将sata m.2 ssd安装到笔记本中，删除sm961中的分区以便系统迁移  
3. 对于不与科目一一起测试的科目三，预先将sm961安装到笔记本中，删除sm961中的分区以便系统迁移

# 考试设备
1. 测试平台陈列在223桌面或货架上
2. 笔记本陈列在6号柜中间，包括电源
3. 6号柜还有256G SM961磁盘，该磁盘记为1号（可能装在笔记本中）
4. 6号柜还有860 sata硬盘一个，该硬盘记为2号
5. 6号柜还有m.2 128g sata协议ssd一个，该硬盘记为3号


# 科目一：台式机拆机与装机

## 考核内容
1. 将台式机拆除为零件状态，需要满足以下条件才可被认为是拆除完成：  

   - 散热、显卡、主板、硬盘、电源均从机箱中拆除，机箱后 IO 挡板被拆除，拆下至少一个主板固定铜柱
   - 散热器、散热器扣具、CPU、内存、M.2 固态硬盘均需从主板上拆除，并妥善保存  
   - 处理器上：旧硅脂基本擦除
   - 电源：拆除所有模组线，并妥善保存
2. 重新装机，需满足以下条件才可认为是装机完成：
   - 处理器上涂抹有适量硅脂  
   - IO面板得到正确安装，拆下的主板固定铜柱被正确地安装回去  
   - 处理器、扣具、M.2硬盘（1号）和内存均被正确安装回主板上  
   - 电源模组线得到正确安装  
   - 电源、主板、sata硬盘（2号）、显卡、散热均正确安装回机箱内，并确保所有螺丝孔位均有正确型号的螺丝固定  
   - 可以正常进入先前已安装的系统
3. 可选：使用WePe在固态硬盘内安装windows10系统，若选择安装windows系统，无需额外完成科目二或科目三  
   参考科目三内容

## 注意事项
1. 注意操作规范性，例如：防静电、避免损坏硬件、注意数据安全
2. 有出现因错误操作导致硬件损坏、数据丢失的，考核成绩不合格
3. 结束后整理台面

# 科目二：更换笔记本固态并进行系统迁移
## 考核内容
1. 拆开笔记本
2. 拆下旧固态硬盘（3号），安装新固态硬盘（1号）
3. 安装笔记本，确保正常开机，功能正常

4. 设置U盘位第一启动项，从 U 盘内的 WePE 系统启动电脑
5. 使用diskgenius或傲梅分区助手完成系统迁移
6. 确保完成迁移后系统功能保持正常

## 注意事项
1. 注意操作规范性，例如：防静电、避免损坏硬件、注意数据安全
2. 有出现因错误操作导致硬件损坏、数据丢失的，考核成绩不合格

3. 注意螺丝刀等工具的使用规范，用力下压再旋转。操作不当导致笔记本滑牙的，考核成绩不合格
4. 结束后整理台面


# 科目三：使用 WePE 在固态硬盘内安装 Windows 10系统
## 考核内容
1. 对于不和科目一一起考核的，使用笔记本进行操作
2. 设置U盘位第一启动项，进入WePE系统
3. 使用傲梅分区助手或diskgenius完成固态硬盘分区（3号或2号）
4. 使用Dism++或windows安装器或ISO内setup.exe安装windows系统
5. 重启，完成OOBE阶段
6. 激活windows
7. 使用SDI或windows自带系统更新完成驱动安装，确保设备管理器中没有未安装驱动的设备
## 注意事项
1. 注意操作规范性，例如：防静电操作，避免损坏硬件，注意数据安全
2. 有出现因错误操作导致硬件损坏、数据丢失的，考核成绩不合格
3. 注意螺丝刀等工具的使用规范，用力下压再旋转。操作不当导致笔记本滑牙的，考核成绩不合格
4. 结束后整理台面


