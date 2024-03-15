# proj355--Diagnosis-of-the-root-cause-of-the-abnormality
基于火焰图的异常根因诊断
## 项目描述
当前Continuous Profiling 已经成为了应用观测不可或缺的手段，在产生海量数据的同事，如何充分发挥其中数据背后的价值也越来关键。
- 在海量的profiling 数据中，如何提取出关键栈问题？
- 在关键栈信息的基础上，如何实现相似栈信息匹配？
- 是否可以持续巡检profiling 数据，去发掘其中的异常点。
## 预期目标
在提供原始数据和故障模型的基础上，实现一套通用的算法，将原有图信息为输入，输出过程结果为关键栈信息，最终判断结果为是否匹配出已知或者详细问题。
## 特征
根因诊断功能应该满足：
- 能够分析出火焰图的关键热点函数、关联热点函数。
- 能够分析出连续时间内采集的火焰图的变化差异或趋势。
- 能从火焰图库里匹配出相似的火焰图。
- 根据热点函数、火焰图的关联分析和相似火焰图，挖掘异常相关的信息，其中火焰图库预设包含相关的异常根因信息。
## 已有参考资料
- SysOM 的可观测和智能监控实践，https://mp.weixin.qq.com/s/7puCDqN1N5qndsSnWfz1CA?poc_token=HF806WWjrw-voHwwAo7kNyetUG0mA6JbKJekW80
- https://www.brendangregg.com/blog/2014-11-09/differential-flame-graphs.html
- https://www.brendangregg.com/blog/2014-10-31/cpi-flame-graphs.html
- https://www.ruilog.com/notebook/view/9ff8def96d9c.html
## 赛题分类
2.5.5 其他算法实现类
## 参赛要求
- 以个人或小组（成员不超过3名）为单位报名，且参与成员必须来自同一所高校的本科生或研究生
- 允许学生参与大赛的多个题目
- 遵循“2024全国大学生操作系统比赛”的章程和技术方案要求
## 难度
高度
## License
MIT
## 所属赛道
2024全国大学生操作系统比赛的“OS功能挑战”赛道
## 项目导师
- 姓名：廖肇燕
- 单位：龙蜥社区；阿里云
- gitee ID：liaozhaoyan
- email：zhaoyan.lzy@alibaba-inc.com
