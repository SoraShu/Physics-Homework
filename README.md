# Phisics-Homework  
>用于储存大物作业  
>本人偷懒用markdown，LaTex佬别骂我QAQ  
>储存了大物攻略  
>储存了20级大物期末试卷答案及回忆版

->[目录](./目录.md)  

## 前言

建立本仓库的原意是作为之前上传的习题解答的补充。~~储存作业只是顺便~~  
相当于习题解答勘误加详解吧。  
~~文件夹中的.md文件用于在github上直接查看，下载查看可选pdf文件。~~  
直接查看和下载查看都请查看pdf文件吧，github并不支持KaTex渲染，大意了。可以看看想看看如何手敲作业的可以瞧瞧.md文件。    
**:warning:请勿抄袭！**

## 课本

课本电子版在仓库根目录下。同时附有我个人整合的官方教材习题解答。也许是版本等问题，习题解答存在较多错误，请仔细甄别。

## 作业  
- 作业范围：每一届可能会有不同，但应该差别不大。
- 本人作业质量：应该还行，两年多的物理竞赛应该不是白学的，想~~抄袭~~借鉴的同学大可放心。本人有强迫症，所以过程相对详细。
- 关于作业：写作业是学习大物不可少的过程，希望大家只是用来参考。你如果想抄袭的话没人拦得住你。
- 关于作业形式：老师当然是要求独立完成啦，一般还是手写吧。听说有部分老师要求使用LaTex完成物理作业，但不是计科的。手写建议使用平板或者数位板，便于修改，最后打印提交。如果有像我一样想要手敲的人，推荐使用markdown，不为什么，轻量且无需配置，markdown赛高！

## 推荐参考书目  
- ~~个人觉得计科的大物课本讲得较浅，想要深入学习的可以使用那几本经典物理竞赛教程。~~
- 高数I。没错，就是高数I。会大量使用到微积分的思想，还有解简单的微分方程。

## 关于攻略

个人在考前整理了一份[备考复习攻略](./攻略/攻略.pdf)，攻略较为详细，虽然事实证明侧重点有问题。希望可作为学习时的辅助材料吧。

整理了一些有可能遇到的常见、实用的解题方法，并且对考前群友的一些疑问做了解答。

## 考试

->[20级大物期末试卷回忆版](./试卷/20级大物II期末试卷回忆版.pdf)

->[20级大物期末试卷答案](./试卷/20级大物II期末试卷答案.pdf)

其中`20级大物期末试卷答案`有我关于考试的一些见解以及对于21级考试的一些推测以及备考建议。

> 此份试卷回忆版以及答案由我与[CandyOre](https://github.com/CandyOre)共同完成。

## 关于~~作死~~手敲作业的建议  
对想要和我一样~~作死~~手敲作业，且和我一样偷懒使用markdown的同学的几点建议：  

1. 熟悉LaTex的公式语法，因为markdown的公式继承自Tex，且使用KaTex(或者其他类似东西)进行渲染。
2. 记住常用符号的转义。如`\int`$\to\int$，`\dot{x}`$\to\dot{x}$。
3. markdown唯一的缺点可能就是不能像LaTex一样自动为公式进行编号，但可使用`\tag{1}`或`\tag*{1}`进行手动编号。
4. 作图可在纸上作图并拍照或用软件绘图。推荐使用HTML标签插入图片，因为markdown自带的插入方法无法调节图片大小。  
例：`<img src=1_12.png width="30%">`其中`1_12.png`是图片的绝对或相对路径，`30%`是图片比例。
5. markdown编辑器无推荐，只要支持数学编辑，有实时预览或者预览加同步滚动就行。同时由于提交需要，注意是否支持生成pdf文件。喜欢同一窗口实时预览的可以使用Typora，不追求实时预览可以使用vscode(vscode在输入公式时有智能补全，推荐新手使用)，并推荐安装插件:   
   1. Markdowm All in One：提供markdown的基本支持，支持生成书签，支持使用快捷键`ctrl+M`进行行间公式插入，连按两次`ctrl+M`进行行内公式插入。
   2. Markdown Preview Enhanced：原用于增强预览功能，但我主要馋它可以利用Chrome浏览器将markdown文件打印成pdf。同时它集成了很多小功能，详见[Markdown Preview Enhanced 中文文档](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/)。

## 实验(实在忍不了，上来吐槽一下)
> 更新于2021.12.22

大物实验是我这学期(大二上)乃至目前为止整个大学生涯中最没有意义又最浪费时间的课。虽然大物实验的老师可能会在上课的时候给你灌输物理怎么怎么重要，大物实验怎么怎么重要，但我想说的是，**如果你是个计科的学生**，那你从大物或者大物实验中**根本**无法学到**任何**能提升你的专业水平或者让你以后工作中能受益的东西，至少它本身并不能。当然这是我的个人意见，如果你觉得老师说得对，那你听老师的。

直入正题。大物实验，计科是开在大二上，考查课。一共完成8个实验，于是有8份实验报告，加上之前会有一节绪论课，算上绪论作业一共是9份。需要注意的是，据老师所说，**只要缺做一次实验整门课挂科**，且**无法补考**，只能重修。期末会有一次笔试考试。

以下是几点建议，以及夹带私货的吐槽：
1. 实验报告的提交方式是自行交到柜子里。由于每年都会出现报告漏统计、报告被搞丢的情况，以及按时提交报告却被记迟交的情况，建议对整份实验报告用拍照、扫描等方式进行备份，并在提交时录制有时间戳的录像。很难想象提交一份报告都要这样防贼似的小心谨慎，这在我看来是数一数二的牛逼。值得一提的是实验报告被弄丢的责任会全算在你头上，所以保险起见，像防贼似的防着这些老师吧。
2. 实验报告的预习部分要求是手写(20级的要求)，如果使用电子版有可能老师不承认并要求你手抄一份。都什么年代了还要求手写……建议当练字。
3. 实验报告的数据记录必须手写，同上。可以copy指导书上的表格并打印出来。
4. 实验报告的其余部分可以采用电子版，打印后提交。
5. 建议使用excel、python或者其他自动化的处理方法进行数据处理以及图像绘制。个人认为是大物实验唯一能锻炼的能力了……
6. 若不想在这门没有意义的课上花费太多时间，可以去找学长学姐要一份实验数据(如果他有存的话)，数据处理表格有一位学长将自己制作的excel表格整理上传到[他的github仓库](https://github.com/efJerryYang/physics-lab_II)。这里引用该学长仓库的readme：
> 本来只是临时存放处理数据和写报告的中间产物，但这一次大物实验改变了我的想法。  
>> 2021-11-8 16:32 迈克尔逊干涉仪，完成钠灯的等厚干涉图样调节，此时已经下课47min，第二节课的同学们已经来到实验室听老师对实验步骤的讲解，教室里还剩下我和同次实验的另外3位同学。调节来调节去就是呈现钠灯等倾干涉图样的结果，要不直接就是干涉条纹消失，重头开始用He-Ne激光调节干涉图像。
> 
> 这0.5学分的考查课，规定缺一次实验直接重修，而与你在课程最终的总得分无关。  
> 本仓库存在的目的是使这类无意义课程浪费的时间减小到最少。

7. 关于期末考核。首先是题量方面，绪论加8次实验一共9个部分，构成9个大题，这9个大题包括选择、填空、和解答题，题量相当大，但有2小时的时间，时间上十分充裕。考核的内容偏简单，但有部分题考得相当细，复习也不一定复习得到，也没有必要在考察课的复习上浪费太多的时间，建议直接蒙或者直接跳。
8. 若遇到某个实验实在做不出来，建议不要怀疑自己，有可能是实验仪器的问题，可以请老师帮忙看。若老师坚持认为是你的问题，也可以换台仪器进行实验。麦克尔孙干涉仪的等厚干涉条纹调不出来也不要心态爆炸，说实话我也做不出来。
9. 请保持心态平和。当老师一脸得意地说着昨天几个人在实验室做了一下午都没做出结果的时候，尽量忍住不要骂他；当老师认真地跟你说物理实验有多重要的时候，尽量不要笑出声；实验实在做不出来的时候，不要钻牛角尖，抄份数据或者编份数据就行，毕竟你的时间宝贵。
10. 再次提醒，实验漏做(在老师那边定义为没交实验报告或没做实验)直接挂，没有补考，直接重修。

真心希望这部分内容你们用不上……每年都被骂的课取消得了……

## 记

最后完善了一遍仓库，这也许也是最后一次commit了。希望这个仓库的内容能帮到学弟学妹，这也是我建立这个仓库的初衷之一。

最后插一句，若仓库内容有误(不包括主目录下的电子版教材与习题解答)，欢迎开issue或者提交pr，我随缘解决。

---
> 更新于2021.12.22，大二上

此仓库的初衷为帮助学弟学妹了解大学物理和大学物理实验的课程内容以及考核形式，并在作业和考试上提供一定指导，在此已基本达成。

若仓库内容有误(不包括主目录下的电子版教材与习题解答)，欢迎开issue或者提交pr。若此仓库有帮到你，也可以点颗星星。
