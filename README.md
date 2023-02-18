# MTWI
  天池"MTWI 2018 挑战赛二：网络图像的文本检测"比赛上
### 一、简介  
  图像文本识别算法 检测文本所在位置 CTPN 识别文本区域内容 CRNN 构建一个识别文字的检测器 得到文本候选框
  <br>

### 二、预训练模型  
  [CRNN-1010.pth](https://pan.baidu.com/s/1yYX1kG1jgQRUdOEZTGqJng?pwd=jqzc)    <br>
  百度云提取码:jqzc

### 三、数据集
  [MTWI 2018 挑战赛二：网络图像的文本检测](https://pan.baidu.com/s/15wO8ebYo_AbAQ3piEy_UUw?pwd=lxvh )<br>
  提取码：lxvh

### 四、环境
 * python 3.10  <br>
 * torch                1.4.0+cu92  <br>
 * torchvision          0.5.0+cu92  <br>
 
### 五、使用方法

### 六、结果
  MTWI 2018 挑战赛中的结果Score:0.656 Precision:0.649 Recall:0.662  <br>
 
### 七、总结
  因为复现的效果还是有一些问题，尤其是在倾斜文本的检测中，个人感觉是在预选检测框时，用文本外接最小矩形与预选框的最大IOU作为检测框，但是倾斜文本本身与预选框的IOU却很小，导致检测框选的不准
