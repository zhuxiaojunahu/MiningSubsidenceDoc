# 采煤沉陷预测分析系统使用说明书

![软件系统启动界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/bg2.png)

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

<center>![软件系统启动界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image002.jpg)  <br>
*图1-1 软件系统启动界面* </center>

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

**（1）首先双击软件安装包【采煤沉陷预测分析系统安装文件.exe】文件，见图3-1。**  <br> 
注：安装时请关闭杀毒软件或防火墙，防止软件安装过程中出现错误。<br>
 
<center> ![系统启动文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image004.jpg) <br>
*图3-1 系统启动文件* </center>

**（2）进入安装界面后点【下一步】，见图3-2。** <br>
<center> ![系统安装界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image006.jpg) <br>
*图3-2 系统安装界面* </center>

**（3）在授权协议界面（图3-3）。** <br>
<center>![授权协议界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image008.jpg) <br>
*图3-3 授权协议界面* </center>

**（4）选择安装路径（图3-4）**  <br>
<center>![选择安装路径](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image010.jpg) <br>
*图3-4 选择安装路径* </center>

**（5）安装成功。**  <br>
<center>![安装成功](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image012.jpg) </center>
 
**（6）安装软件辅助软件**  <br>
软件安装成功后，提示安装Surfer8.0，如果系统中已经安装Surfer8.0，可以去掉Surfer8.0前的选项框，再点击【完成】即可；如果未去选项框中的√，软件会默认安装Surfer8.0。  <br>
软件完成安装后，确保系统中已经安装相关辅助软件正确版本，否则会影响软件的使用。

**（7）软件启动。** <br>
软件使用时，需要在电脑USB端口，插入软件商提供的配套加密狗，如图3-5 <br>
<center>![软件加密狗](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image014.jpg) <br>
*图 3-5 软件加密狗* </center>

**（7）软件首次运行** <br>
<center>![软件首次运行界面](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image016.jpg) <br>
*图3-6 软件首次运行界面* </center>

软件首次运行，会配置系统文件以及将注册信息发送给服务器，以便今后的软件维护和更新。

## 4 开采沉陷预计的概率积分法模型
### 4.1 概率积分法地表沉陷预计的数学模型
概率积分法是我国煤矿领域广泛应用的地表沉陷预计模型，几乎各矿务局都有相应的地表沉陷预计参数。因此，本系统是基于概率积分法模型编写而成。
概率积分法沉陷预计的基本原理如下： <br>

<center>![地表任意点任意方向的预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image018.png) <br>
*图4-1 地表任意点任意方向的预计* </center>

**（1）地表任意点A(x，y)的下沉值W(x，y)** <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image021.png)    	                                       **（4-1）** <br>
其中:
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image022.png) <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image023.png) <br>
 
式中：
*Wcm*—充分采动条件下地表最大下沉值， ； <br>
*m*—采出煤层厚度； <br>
*q* —地表下沉系数； <br>
*α*—煤层倾角； <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image027.jpg) —为待求点在走向和倾向主断面上投影点处的下沉分布系数； <br>
*l，L*—为采区拐点平移后走向长度及倾斜方向在地表的计算开采宽度； <br>
*r，r1，r2*——分别为走向、下山、上山方向的主要影响半经； <br>
*x、y*——待求点坐标。 <br>

**（2）地表任意点A(x，y)沿φ方向倾斜变形值T(x，y)j** <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image028.png) **（4-2）** <br>
式中：  <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image030.png)——待求点的最大倾斜值，mm/m； <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image032.png)——最大倾斜值方向与OX轴的夹角(沿逆时针方向旋转)，度； <br>
*Tx，Ty*——分别为待求点沿走向和倾向主断面上投影点处迭加后的倾斜变形值，mm/m。 <br>

**（3）地表任意点A(x，y)沿φ方向的曲率变形K(x，y)j** <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image035.png)**（4-3）** <br>
式中： <br>
*Kx，Ky*——分别为待求点沿走向及倾向在主断面投影处迭加后的曲率值。 <br>

**（4）地表任意点A(x，y)沿φ方向的水平移动值U(x，y)j**。 <br>
![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image036.jpg)**（4-4）** <br>
式中：φu——为最大水平移动方向与OX轴的夹角 <br>
*Ux，Uy*——分别为待求点沿走向和倾向在主断面投影点处的水平移动值，mm。对于倾斜方向需加Cy′•Wcm•ctgθ 。 <br>

**（5）地表任意点A(x，y)沿φ方向的水平变形值ε(x，y)j** <br>
 ![预计公式](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image039.png)**（4-5）** <br>
式中：     <br>      
*εx，εy*——为待求点沿走向及倾向在主断面投影处迭加后的水平变形值。 <br>

### 4.2 概率积分法预计参数及其反演方法

在一个地表观测站的观测工作结束并完成了观测成果的整理与分析之后，应进一步求取这个观测站的实测参数。

概率积分法关于下沉盆地的参数共包含8个，即下沉系数q，主要影响角正切 tanβ，水平移动系数b，左、右、上、下拐点偏移距s1、s2、s3、s4，开采影响传播角θ。其所有参数都是在充分采动情况下的参数。

本系统采用遗传算法进行概率积分法参数的反演，遗传算法（Genetic Algorithm， GA）是一种模拟达尔文自然选择和遗传机制，在计算机上进行自适应概率性全局寻优搜索算法，它最先是由美国Michgan大学的John Holland于1975年提出的。

遗传算法是一种基于生物自然选择与遗传机理的随机搜索算法，与传统搜索优化算法不同，遗传算法从一组随机产生的称为“种群”的初始解开始搜索过程。种群中的每个个体是问题的一个解，称为“染色体”。染色体是一串符号，比如一个二进制字符串。这些染色体在后续迭代中不断进化，称为遗传。在每一代中用“适值”来测量染色体的好坏，生成的下一代染色体称为后代。后代是由前一代染色体通过交叉或者变异运算形成的。在新一代形成过程中，根据适度的大小选择部分后代，淘汰部分后代，从而保持种群大小是常数。适值高的染色体被选中的概率较高，这样经过若干代之后，算法收敛于最好的染色体，它很可能就是问题的最优解或次优解。

遗传算法具有无需对函数进行逆向处理和多参数反演能力，所以基于遗传算法的参数反演就不需要对函数进行线性化以及只需提供参数的范围，同时对搜索空间中的多个点进行评估，有效避免了常规算法对初值依赖性强、易陷入局部极小值等缺陷。所以考虑遗传算法以上优点，本系统采用遗传算法对概率积分法的参数进行反演。

基于遗传算法的概率积分法参数反演的步骤如图4-2：<br>
<center>![反演的步骤](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image040.jpg) </center>

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

## 5 开采沉陷预计使用说明

在启动界面选项中选择【开采沉陷预计】按钮，进入开采沉陷预计功能模块，其主界面如图5-1所示。

<center>![反演的步骤](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image044.jpg) <br>
*图5-1 开采沉陷预计功能模块* </center>

该预计部分的菜单结构如下：
> **工作面准备**
>>初始化预计工程
>>新建预计文件（EXCEL）
>>打开示例文件（EXCEL）
>>导入工作面（EXCEL）

>**生成预计点**
>>自动生成预计点
>>框选预计点范围
>>指定预计点方向
      
>**沉陷预计**
>>预计点计算
>>沉陷极值计算

>**数据输出**
>>打开DataResults文件夹
>>删除DataResults文件夹下文件
>>预计点输出
>>预计极值点输出
>>预计结果文件夹另存为

>**设置**
>>选项

>**功能模块**
>>生成等值线图（Surfer）
>>CAD辅助模块

>**帮助**
>>内容
>>搜索
>>软件更新
>>更新设置
>>关于我们
		
		
### 5.1 数据准备

沉陷预计部分的数据是以EXCEL格式导入的，具体格式见附录1或软件安装路径下\Date\工作面预计参数.xls为软件的示例文件。 <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image045.png) <br>
*图5-2 预计参数文件* </center>

其格式为： <br>
第一行为各个参数的名称（见图5-3）： <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image047.jpg) <br>
*图5-3 开采沉陷预计参数表头* </center>

前十二个填写项目为：
> * 工作面名称：所要预计的工作面的名称
> * 走向方位角：所要预计工作面走向的方位角，其单位为度。（正北方向顺时针旋转至煤层倾斜方向，再逆时针旋转90度，即工作面走向方位角）
> * 采厚：工作面煤层采厚，单位：mm
> * 煤层倾角：煤层的倾角
> * 下沉系数、主要影响角正切、水平移动系数、传播角（主要影响传播角）和拐点偏移距
注：拐点偏移距有四个数据：上拐点偏距，下拐点偏距，左拐点偏距，右拐点偏距。具体如下图5-4。

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image049.jpg) <br>
图5-4 开采沉陷预计的拐点偏移距 </center>

余下的数据为每个工作面的角点，由每个角点的X、Y（大地坐标）、H组成，依次按这种格式写入，点数不限，建议不超过8个角点。 <br>
注：写入点时按逆时针顺序依次写入。

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image051.jpg) <br>
*图5-5 预计工作面角点数据* </center>

第一行以后，依次写入每个工作面的具体参数，一个工作面占用一行。 <br>
具体参考附录1或示例文件（安装路径\Date\工作面预计参数.xls）

### 5.2 导入预计数据
点击【文件】菜单下【从EXCEL导入工作面】，选择准备好的文件，导入即可（图5-6）。 <br>

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image053.png)  <br>
*图5-6 预计数据文件导入* <br> </center>

导入后，系统将在左侧栏显示导入工作面的名称以及系统右侧显示所有工作面的参数，以便检查（图5-7）。 <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image055.jpg)  <br>
*图5-7 导入数据的检查* </center>

### 5.3 工作面角点平面坐标的获取

由于预计时工作面比较多，每个工作面的角点也比较多，输入角点的坐标相当繁琐，系统中提供了一种在CAD图中自动获取角点平面坐标的功能。 <br>
首先，用CAD2004打开工作面的CAD图，然后，点击菜单【文件】中的【从CAD中获取角点】，便会在CAD中看见选取角点的提示，按照提示即可选取角点，最终生成符合本系统导入文件的格式EXCEL文件。如图5-8所示。 <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image057.jpg)  <br>
图5-8 工作面角点平面坐标的获取 <br> </center>
注：（1）如果CAD图中的工作面角点带有高程信息，则导出的文件中含有每个角点的坐标；如果CAD图中的工作面角点不带有高程信息，则导出的角点高程都为零，各角点的高程数据仍需要手工填写。 <br>
（2）CAD的图中工作面的坐标必须是在统一的坐标系之下。 <br>

### 5.4 工作面检核

**（1）工作面显示** <br>
点击软件【示意图】选项，显示图形绘制界面，如图5-9，通过示意图检核工作面数据是否正确。 <br>

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image061.jpg)  <br>
*图5-9 图形绘制界面* </center>

**（2）从CAD图中检核工作面** <br>
打开采掘工程平面图或者工作面布置图（CAD图），点击菜单【文件】中的【从CAD检核工作面】，软件自动将工作面示意图叠加在CAD底图中，检核工作面选取是否正确。 <br>

### 5.5 预计选项设置 <br>
点击菜单中【设置】中【选项】，显示设置界面，如下图5-10：<br>

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image063.jpg)   <br>
*图5-10 开采沉陷预计选项窗口* </center>

如图5-10所示，在预计之前可预计细节进行自助设置，如地表点设置、工作面剖分设置、预计文件输出路径和剖分显示模式。 <br>

**（1）地表点设置** <br>
在地表点设置一栏中，用户可对地表预计点进行设置，取点可根据用户所定义的取点间隔由软件自动生成，取点间隔为自动生成预计点时，相邻点的X和Y上的间隔距离，任意点的预计方向为生成预计点时默认的每个点的方向；用户如果相对某些点进行单独预计，可以事先编写好预计点文件，点选“选取自定义预计点文件”在设置好的文件路径下选取预计点文件，从而实现兴趣点变形值的预计。 <br>
预计点方向的设置形式如图5-10示，在最后一栏中填写（单位为xx°xx′xx″） <br>

**（2）工作面剖分设置** <br>
工作面剖分设置如图5-11所示，用户可以对预计工作面的剖析情况进行选择和设置。 <br>
> “根据最小采深自动剖分”选项，如图5-12所示软件会根据工作面采深情况，智能选取最适宜的工作面剖分尺寸生成预计工作面；
> “人工设定工作面剖分大小” 如图5-12所示，用户可以根据现场资料和预计经验自主设定工作面 <br>

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image065.jpg)    <br> 
*图5-11工作面剖分设置* </center>

<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image067.jpg)  <br>
*图5-12人工设定工作面剖分大小* </center>

剖分大小，以选取最适宜的工作面剖分大小减小误差，提高预计精度。

**（3）预计文件输出路径** <br>
预计文件输出路径，如图5-13所示，用户可以选择“输出到软件文件夹下”，此时预计文件存放在文件安装路径下的TEMP文件夹下；用户也可根据需要选择“自定义输出路径”，此时预计结果文件会存放在用户所指定的任意文件夹下。 <br>
如图5-13所示，“预计前自动删除TEMP文件夹下文件”和“预计完成后计算沉陷极值”两项为复选项，用户可以根据需要自行选择，建议全部选取。 <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image069.jpg)   <br>
*图5-13预计文件输出路径* </center>

**（4）剖分显示模式** <br>
剖分显示模式，如图5-14所示，用户可以在此处设置剖分模式的显示模式，根据用户的选择，可以在示意图一栏中看到用户设置的剖分模式下所剖分的工作面细节情况，本项操作需输入密码，具体请咨询软件所有者。 <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image071.jpg)   <br>
*图5-14分显示模式* </center>

### 5.6 生成预计点

系统中生成预计点的方式有三种方式。 <br>
>**第一种方式：自动生成预计点**
点击菜单中【生成预计点】中【自动生成预计点】，系统自动生成点的数据文件，生成的点数据文件在安装路径\Date\AutoPoint.txt。
文件的格式： <br>
点名，点的X坐标（大地坐标），点的Y坐标（大地坐标），预计方向 <br>

>**第二种方式：在图形中框选范围** <br>
点击菜单中【生成预计点】中【框选范围】或者在系统“示意图”区域工具栏中按 按钮，然后点击鼠标框选所要预计的范围，即可在框选范围内生成指定间隔的点，生成的点数据文件在安装路径\Date\AutoPoint.txt。 <br>
同样，点击菜单中【生成预计点】中【指定方向】或者在系统“示意图”区域工具栏中按 按钮，然后点击鼠标指定一条直线，即可在指定的直线方向生成指定间隔的点，生成的点数据文件在安装路径\Date\AutoPoint.txt。 <br>

>**第三种方式：手工输入点的坐标** <br>
系统还可以通过修改安装路径\Date\AutoPoint.txt文件来输入点的坐标。 <br>
注：手工输入点的坐标时应按照文件的格式输入。

### 5.7 沉陷预计 <br>

点击菜单【预计】中【沉陷预计】，即可预计准备好的点，预计完成后在系统自带的表格中查看预计结果，如下图5-16： <br>
<center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image077.jpg)   <br>
*图5-16 预计结果查看窗口* </center>

### 5.8 预计结果输出

系统有两种方式输出结果：
>（1）点击【数据输出】中【预计点输出】，可以EXCEL方式输出预计点的结果。表格输出的结果有：点序号、点X坐标、点Y坐标、下沉、倾斜、曲率、水平移动、水平变形、预计方向+90度的倾斜、曲率、水平移动、水平变形。<br>
 <center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image079.jpg)  <br>
*图5-17 开采沉陷预计结果输出表* </center>

>（2）在软件安装路径\DataResults文件夹下存放所有预计结果的数据文件。

 <center>![预计参数文件](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image081.jpg)   <br>
图5-18 自动存放的预计结果数据文件 </center>

>预计结果数据文件包括： <br>
下沉值预计结果文件w.dat； <br>
指定预计方向倾斜变形值预计结果文件i.dat； <br>
指定预计方向曲率变形值预计结果文件k.dat； <br>
指定预计方向水平移动值预计结果文件u.dat； <br>
指定预计方向水平变形值预计结果文件e.dat； <br>
指定预计方向+90度倾斜变形值预计结果文件it.dat； <br>
指定预计方向+90度曲率变形值预计结果文件看kt.dat； <br>
指定预计方向+90度水平移动值预计结果文件ut.dat； <br>
指定预计方向+90度水平变形值预计结果文件et.dat。 <br>

各预计结果文件的数据格式为： <br>
点名，X坐标（大地坐标），Y，预计值

### 5.9 绘图 

本系统支持自主绘制地表变形等值线图，用户需自行安装Surfer软件，通过后台调用Surfer，绘制预计图。点击【功能模块】中【生成等值线Surfer】，进入绘图界面，如下图5-19： <br>
 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image083.jpg)   <br>
*图5-19 绘图界面* </center>

操作步骤（以地表下沉为例）如下： <br>
> （1）点击【等值线】中【等值线设置选项】，会弹出如图5-20所示对话框，用户可根据预计地区实际情况对所要生成的变形等值线的样式进行自主设置，如：等值线字体大小，等值线间隔，等值线标注间隔，第一条等值线值等；

> （2）点击【文件】中【打开下沉w文件】，选择前述第二种预计结果输出方式的预计结果数据文件（存放在安装路径\DataResults下），如选择w.dat。

> （3）等待界面右下角出现“数据导入完毕”，点击【等值线】中【显示等值线】，即可在软件画图区域看到所要预计区域的等值线图（如图5-20）。如图5-20所示，在本界面的右侧会显示出所绘制的等值线的极值情况。

> （4）点击其他的菜单显示相应的图形，如三维图形、三维线框图形、等值线图像等。如下图5-20：

>  （5）点击【导入CAD】中的【导入下沉等值线】可以将生成的地表下沉等值线图按原坐标输入到当前打开的CAD中。

> （6）如图5-20下部所示，“等级划分”，用户根据现场资料以及相关的章程设置不同的临界值，以便于绘制出相应的损害等级图. <br>
具体操作方法为：1、“等值线基本设置”中设置各损害等级曲线的颜色；<br>
2、在“下沉w设置”中勾选 “绘制等级图”，并根据具体情况设置各等级数值；<br>
3、点击【文件】中相对应的【打开下沉w文件】，此时绘图界面会出现相应的损害等级图 <br>

 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image085.jpg)  <br>
*图5-19 基本等值线设置* </center>

 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image087.jpg)   <br>
*图5-20等值线选项* </center>

 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image089.jpg)  <br>  
*图5-21 开采沉陷预计等值线绘制与编辑处理* </center>
 
 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image091.jpg)  <br> 
*（1）三维立体图形* </center>

 <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image093.jpg)   <br>
*（2）彩色等值线图像* </center>

### 5.10 应用案例

**案例1** <br>
案例1采用中国矿业大学出版社出版的《矿山开采沉陷学》书中187页第四题中的工作面及相应的参数。 <br>
工作面走向长150m，倾向长100m，采厚 =1m，平均采深H=100m，水平煤层，工作面左下角坐标为（0，0）。概率积分法参数为：下沉系数 ，主要影响角正切 ，拐点偏移距 ，水平移动系数 ，开采影响传播角  <br>

准备数据文件如下：<br>
  <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image107.jpg)    <br>
*图 5-16 预计准备数据文件* </center>

> 软件操作步骤： <br>
（1）	准备数据文件 <br>
（2）	点击菜单【文件】中【从EXCEL导入文件】，选择准备好的文件。 <br>
（3）	点击菜单【生成预计点】中【自动生成预计点】点击菜单【预计】中【沉陷预计】，则所要预计的点将进行预计。 <br>
（4）	在安装路径\TEMP文件下查看预计的结果，同时画出等值线。 <br>

  <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image109.png)   <br> 
*图 5-17 预计范围下沉等值线* </center>

如果需要预计指定的点，则在步骤（2）时修改安装路径\Date\AutoPoint.txt，按照格式修改即可。如预计（100,0）处，预计方向为135°的点地表移动变形情况，则修改AutoPoint.txt如图

  <center>![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image111.jpg)  <br>
*图 5-17 修改后AutoPoint.txt文件* </center>

使用本软件对上述工作面的地表一个任意点和主断面进行移动变形预计，其任意点坐标为（100， 0），预计方向为135°，并生成走向和倾向主断面变形曲线。

<center>*表 5-1预计结果对比表* <br>
  ![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表5-1.png)  <br> </center>

表5-1给出了手算和程序计算结果，计算最大的相对误差为0.19%。所以由上计算结果可见，本系统的预计部分地表移动变形值计算程序基本正确。

## 6 概率积分法参数反演使用说明

开采沉陷概率积分法预计参数反演基于遗传算法编写。其主界面如图6-1所示。

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image113.jpg) <br>
*图6-1 开采沉陷概率积分法预计参数反演分析主界面* </center>

**概率积分法预计参数反演部分的菜单结果如下：** <br>
>反演文件
>>新建空数据文件
>>导入反演数据

>参数反演
>>根据w反演 > q tanβ θ S
>>下沉值、水平移动联合反演 > q tanβ θ S b

>求参结果
>>下沉拟合图
>>水平移动拟合图
>>输出参数反演报告

>设置
>>选项

### 6.1 数据导入

参数反演需导入的原始数据采用EXCEL文件格式，可通过地表移动观测数据整理后的文件格式转换为EXCEL文件格式。图6-2为导入的地表沉陷观测数据，图6-3为求参工作面及遗传算法相关参数的设置。

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image115.png) <br>
图6-2 实际观测值的数据文件准备 </center>

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image117.jpg)  <br>
图6-3 工作面与遗传算法参数设置文件 </center>

具体格式参考软件安装路径\Date\某矿反演反演数据.xls

### 6.2 反演参数

数据导入系统之后，点击【参数反演】，系统自动反演概率积分法预计参数，详细求参结果显示在软件右侧面板纸上，软件反演结果会显示在软件的显示文本框中见图6-6，同时弹出遗传算法收敛速度图，以便查看反演的情况。 

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image119.jpg)   <br>
*图6-5 遗传算法算法收敛图* </center>

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image121.jpg)    
*图6-6 显示反演结果* </center>

### 6.3 拟合图

点击【求参结果】中拟合图，显示实测点与根据反演参数预计点的下沉值的拟合图。

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image123.jpg)    <br>
*图6-7 实测下沉与拟合下沉对比图* </center>

### 6.4 反演求参报告生成
点击【求参结果】中【输出参数反演报告】
系统自动生成Word格式的文本报告，如图6-8。

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image125.jpg)  <br>
*图6-8 Word格式的参数反演报告* </center>

### 6.5 应用案例

**案例1** <br>
案例1采用某煤矿工作面观测站实测数据。该工作面采用倾向长壁综采放顶煤采煤法开采，全部垮落法管理顶板，其基本见表7-1。工作面与地面观测站井上下对照见图5-1所示。

<center> *表6-1工作面基本情况表* <br>
![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表6-1.png)  <br> </center>

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image127.png)  <br>
图6-9工作面与地面观测站井上下对照图 </center>

观测站原始数据如下：

<center> *表6-2工作面观测站观测数据* <br>
![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表6-2.png)  <br> </center>

在系统参数反演部分不需要前期做将大地坐标转换成工作面坐标的准备，只需要提供工作面左下角和工作面倾向方向的方位角就可，软件自动转换成相应的坐标，所以从工作面的CAD图中提取左下角坐标X=XXX8950m，Y=XXX89250m，工作面倾向方向的方位角225°。

遗传算法参数设置和编码精度采用系统文件中默认值。

概率积分法参数范围：

<center> *表6-3概率积分发参数范围* <br>
![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表7-3.png)  <br> </center>

>软件操作步骤：
（1）将实测数据和求参参数准备成EXCEL文件（见图6-10和图6-11），点击文件菜单中【导入反演数据】，导入到系统中；
（2）点击菜单【参数反演】中【根据下沉值反演参数】进行求参，求参结果结果在系统文本显示区域显示；
（3）点击菜单【求参结果】中【下沉拟合图】查看拟合效果；
（4）点击菜单【求参结果】中【输出参数反演报告】，系统自动生成参数反演的报告。

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image129.png)  <br>
*图6-10 观测站实测数据文件* </center>

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image131.png)   <br>
*图 6-11参数反演的参数设置文件* </center>

<center> *表6-4根据观测站下沉曲线拟合求取的概率积分法参数*  <br>
![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表6-4.png)  <br> </center>

<center> *表6-5按概率积分法模型拟合下沉值与实测下沉值对比表*  <br>
![预计](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/表6-5.png)  <br> </center>

  <center>![反演](https://github.com/zhuxiaojunahu/MiningSubsidenceDoc/raw/master/DocImage/image133.jpg)   <br>
*图6-12地表移动观测线S线地表下沉曲线拟合图* </center>

从表7-5和图7-12中中看出预计值和实测值的拟合比较吻合且残差的平方和[VV]=6826，说明求出的参数是准确的，符合工程预计的要求。
