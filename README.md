# 采煤沉陷预测分析系统使用说明书

## 1 采煤沉陷预测分析系统简介
煤炭工业是关系能源安全和国民经济命脉的重要基础产业，这对我们煤炭行业的技术革新提出了新的要求。煤炭工业在保障国民经济和社会发展需要的同时，必须转变经济增长方式，加快结构调整，走资源利用率高、安全有保障、经济效益好、环境污染少和可持续的发展道路。

只有准确的预计矿山开采引起的沉陷问题，才能对环境的破坏提前做出评估，为开发后的矿山环境保护和综合治理提供依据。开采沉陷预计不仅对国家经济建设和环境保护有着重要的意义，而且对在建筑物、铁路和水体下（三下）的采煤有着十分重要的作用。

有了准确的地表移动变形的预计值，才能在建筑物下采煤时，判别出建筑物是否受开采影响以及受开采影响的程度，并作为受影响建筑物进行维修、加固、就地重建或地下开采措施被采用的依据；才能在水下采煤时，确定合理的水下开采的上限；才能在铁路下采煤时，根据预计的结果判断铁路下开采的可能性,估算铁路维修工作量和材料用量,安排维修计划，通过及时的维修铁路的方式解放铁路下的压煤；才能准确的确定井巷和各类敏感建筑物的煤柱留设范围，避免导致盲目圈定范围、浪费资源和危险的发生；才能在进行承压水上采煤时，确切了解煤层地板移动、变形和应力重新分布的规律，实现安全生产。

总之，对煤层进行开采沉陷预计对地下采煤和地面建筑物、铁路、环境的保护都是十分重要的，有时甚至是必不可少。

本系统基于开采沉陷概率积分法模型开发，概率积分法是我国《建筑物、水体、铁路及主要井巷煤柱留设与压煤开采规程》中推荐的并且在我国应用最广泛的煤矿开采沉陷预测方法。
系统由两大部分模块组成：
> * 开采沉陷预计模块
> * 实测资料参数反演分析模块

本系统主要特点有：
> * 预计结果具有较高的准确性、稳定性和可靠性
> * 软件界面友好、操作简单、预计结果可视化
> * 功能强大，满足不同地质采矿条件的沉陷预计问题

**软件系统启动界面**
![软件系统启动界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image002.jpg)

------
## 2 软件运行环境
操作系统：Window XP、Window7或者Window 10
运行软件需要安装相关辅助软件：
> * AutoCAD2004或者2006；
> * Surfer8.0；
> * Office Excel2003、2007、2010或者2013；
> * Office Word2003、2007、2010或者2013；

版本：3.0

------
## 3 软件安装方法

（1）首先双击软件安装包【采煤沉陷预测分析系统安装文件.exe】文件，见图3-1。
注：安装时请关闭杀毒软件或防火墙，防止软件安装过程中出现错误。
**图3-1 系统启动文件**
![系统启动文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image004.jpg)

（2）进入安装界面后点【下一步】，见图3-2。
**图3-2 系统安装界面**
![系统安装界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image004.jpg)

（3）在授权协议界面（图3-3）。
**图3-3 授权协议界面**
![授权协议界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image008.jpg)

（4）选择安装路径（图3-4）
**图3-4 选择安装路径**
![选择安装路径](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image010.jpg)

（5）安装成功。
![安装成功](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image012.jpg)
 
（6）安装软件辅助软件
软件安装成功后，提示安装Surfer8.0，如果系统中已经安装Surfer8.0，可以去掉Surfer8.0前的选项框，再点击【完成】即可；如果未去选项框中的√，软件会默认安装Surfer8.0。
软件完成安装后，确保系统中已经安装相关辅助软件正确版本，否则会影响软件的使用。

（7）软件启动。
	软件使用时，需要在电脑USB端口，插入软件商提供的配套加密狗，如图3-5
**图 3-5 软件加密狗**
![软件加密狗](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image014.jpg)

（7）软件首次运行
**图3-6 软件首次运行界面**
![软件首次运行界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image016.jpg)

软件首次运行，会配置系统文件以及将注册信息发送给服务器，以便今后的软件维护和更新。

## 4 开采沉陷预计的概率积分法模型
### 4.1 概率积分法地表沉陷预计的数学模型
概率积分法是我国煤矿领域广泛应用的地表沉陷预计模型，几乎各矿务局都有相应的地表沉陷预计参数。因此，本系统是基于概率积分法模型编写而成。
概率积分法沉陷预计的基本原理如下：

![地表任意点任意方向的预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image018.png)
*图4-1 地表任意点任意方向的预计*

**（1）地表任意点A(x，y)的下沉值W(x，y)**
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image021.png)    	                                       **（4-1）**
其中:
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image022.png)
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image023.png)
 
式中：
Wcm—充分采动条件下地表最大下沉值， ；
m—采出煤层厚度；
q —地表下沉系数；
α—煤层倾角；
 —为待求点在走向和倾向主断面上投影点处的下沉分布系数；
l，L—为采区拐点平移后走向长度及倾斜方向在地表的计算开采宽度；
r，r1，r2——分别为走向、下山、上山方向的主要影响半经；
x、y——待求点坐标。

**（2）地表任意点A(x，y)沿φ方向倾斜变形值T(x，y)j**
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image028.png) **（4-2）**
式中： 
 ![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image030.png)——待求点的最大倾斜值，mm/m；
 ![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image032.png)——最大倾斜值方向与OX轴的夹角(沿逆时针方向旋转)，度；
Tx，Ty——分别为待求点沿走向和倾向主断面上投影点处迭加后的倾斜变形值，mm/m。

**（3）地表任意点A(x，y)沿φ方向的曲率变形K(x，y)j**
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image035.png)**（4-3）**
式中：
Kx，Ky——分别为待求点沿走向及倾向在主断面投影处迭加后的曲率值。

**（4）地表任意点A(x，y)沿φ方向的水平移动值U(x，y)j**。
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image036.jpg)**（4-4）**
式中：φu——为最大水平移动方向与OX轴的夹角
Ux，Uy——分别为待求点沿走向和倾向在主断面投影点处的水平移动值，mm。对于倾斜方向需加Cy′•Wcm•ctgθ 。

**（5）地表任意点A(x，y)沿φ方向的水平变形值ε(x，y)j**
 ![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image039.png)**（4-5）**
式中：          
εx，εy——为待求点沿走向及倾向在主断面投影处迭加后的水平变形值。

###4.2 概率积分法预计参数及其反演方法
在一个地表观测站的观测工作结束并完成了观测成果的整理与分析之后，应进一步求取这个观测站的实测参数。

概率积分法关于下沉盆地的参数共包含8个，即下沉系数q，主要影响角正切 tanβ，水平移动系数b，左、右、上、下拐点偏移距s1、s2、s3、s4，开采影响传播角θ。其所有参数都是在充分采动情况下的参数。

本系统采用遗传算法进行概率积分法参数的反演，遗传算法（Genetic Algorithm， GA）是一种模拟达尔文自然选择和遗传机制，在计算机上进行自适应概率性全局寻优搜索算法，它最先是由美国Michgan大学的John Holland于1975年提出的。

遗传算法是一种基于生物自然选择与遗传机理的随机搜索算法，与传统搜索优化算法不同，遗传算法从一组随机产生的称为“种群”的初始解开始搜索过程。种群中的每个个体是问题的一个解，称为“染色体”。染色体是一串符号，比如一个二进制字符串。这些染色体在后续迭代中不断进化，称为遗传。在每一代中用“适值”来测量染色体的好坏，生成的下一代染色体称为后代。后代是由前一代染色体通过交叉或者变异运算形成的。在新一代形成过程中，根据适度的大小选择部分后代，淘汰部分后代，从而保持种群大小是常数。适值高的染色体被选中的概率较高，这样经过若干代之后，算法收敛于最好的染色体，它很可能就是问题的最优解或次优解。

遗传算法具有无需对函数进行逆向处理和多参数反演能力，所以基于遗传算法的参数反演就不需要对函数进行线性化以及只需提供参数的范围，同时对搜索空间中的多个点进行评估，有效避免了常规算法对初值依赖性强、易陷入局部极小值等缺陷。所以考虑遗传算法以上优点，本系统采用遗传算法对概率积分法的参数进行反演。

基于遗传算法的概率积分法参数反演的步骤如图4-2：
![反演的步骤](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image040.jpg)

> * 第1步：数据准备。工作面的相关信息（名称、采深、采厚、倾角、走向长、倾向长）、参数的范围及其参数精确到小数点后几位、实测数据（点号、坐标、下沉值、水平移动值）和遗传算法参数（种群大小、迭代次数、选择操作方式、交叉概率、变异概率）。
> * 第2步：求取参数二进制长度。根据参数范围和精度，求取每个参数所有可能出现情况的个数，即编码所需的二进制长度。
> * 第3步：种群生成。根据每个参数二进制的长度和范围，随机生成一串二进制数。
> * 第4步：解码。将种群解码成对应的实数。
> * 第5步：根据生成并解码的参数预计实际点的下沉值， 。
> * 第6步：用适应度函数来判断生成的一组参数的适应度，从而计算下面被选择的概率。
> * 第7步：选择操作。
> * 第8步：交叉操作。
> * 第9步：变异操作。
> * 第10步：经过交叉和变异的种群代入第4步，直到达到迭代次数。
> * 第11步：最终输出经过N次迭代后的种群，这些种群是适应度最好的种群。
