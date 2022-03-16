<center><font size=10; >A CLOSER LOOK AT FEW-SHOT CLASSIFICATION</font></center>

***

<br>
#<center>Abstract</center><br>
其实这篇文章就是做了几个实验。

1. a consistent comparative analysis of several representative few-shot
classification algorithms, with results showing that deeper backbones significantly reduce the performance differences among methods on datasets with limited domain differences
<br>

2. a modified baseline method that surprisingly achieves competitive performance when compared with the state-of-the-art on both the miniImageNet and the CUB datasets
<br>

3. a new experimental setting for evaluating the cross-domain generalization ability for few-shot classification algorithms.<br>

#<center> <font size=10>Conclusions</font ></center>  

1. 第一个实验就是说深的网络结构让不用的methods差距变小。
<br>

2. 第二个结果是说他把classifier换成了distance based （cosine）的baseline++得到了很好的效果
<br>

3. 就是说目前的这个few-shot methods 不能很好解决domain shift 的问题。


