# Machine Learning Testing:Survey, Landscapes and Horizons

作者：Jie M. Zhang, Mark Harman, Lei Ma, Yang Liu

主要内容：测试性能、测试组成、测试流程、应用场景
 
   分析研究趋势和重点、总结挑战和方向

软件测试含义： any activity that aims to detect the differences between existing and required behaviour.

ML bug: any imperfection in a machine learning item that causes a discordance between the existing and the required conditions.

ML 测试：. Machine Learning Testing (ML testing) refers to any activities designed to reveal machine learning bugs.



## ML测试

在线测试

离线测试

模糊测试

基于搜索的测试

## Test Orcle
作用:检测程序是否出错
常见的有：变质关系、交叉引用、模型评估指标等

## 鲁棒性
 **测量方法**：在存在噪声的情况下检测系统的正确性，一个稳健的系统应该在有噪声的情况下检查系统的正确性
 **指标**：:Moosavi-Dezfooli等人：
&emsp;1)点态鲁棒性，即输入变化最小的分类器不具有鲁棒性;
&emsp;2)对抗频率，表示改变一个输入改变分类器结果的频率;
&emsp;3)对抗严重度，表示输入与其最近的对抗样本之间的距离。
Tjeng等人：提出使用测试输入与其最近的对抗样本之间的距离来衡量鲁棒性。

	 
	 
## 挑战
网络没有显式分支
网络可能高度非线性
存在可拓展性问题