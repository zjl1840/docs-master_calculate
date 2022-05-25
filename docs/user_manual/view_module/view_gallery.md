
## 1 ECharts 图库

!!! Abstract ""
    ECharts 属于 Apache 基金会下，一个基于 JavaScript 的开源可视化图表库，提供了功能强大的图表和可视化库。

### 1.1 表格

!!! Abstract ""
    表格是数据的详情罗列，能看到明细信息，表格包含汇总表和明细表。  
    **提示：** 明细表支持分页展示。

!!! Abstract ""
    汇总表格

    ![echarts汇总表](../../img/view_generation/view_gallery/ECharts/echarts汇总表.png){ width="900px" }

!!! Abstract ""
    明细表格

    ![echarts明细表](../../img/view_generation/view_gallery/ECharts/echarts明细表.png){ width="900px" }

### 1.2 指标卡

!!! Abstract ""
    通过文字、数字和符号的合理排版，对数据进行一目了然的展示。指标卡由看板标签和看板指标组成，标签由数据的维度决定，指标由数据的度量决定。  
    **提示：** 指标卡当前不支持跳转设置。

!!! Abstract ""

    ![echarts指标卡](../../img/view_generation/view_gallery/ECharts/echarts指标卡.png){ width="900px" }  
    **注意：** 指标卡当前只支持数值类型的数据汇总。

### 1.3 文本卡

!!! Abstract ""
    展示文本字段的实际文字可使用文本卡，文本卡可展示该字段原本的内容、时间、文本信息等。  
    **提示：** 文本卡拖入的字段必须是“维度”类型。

!!! Abstract ""

    ![echarts文本卡](../../img/view_generation/view_gallery/ECharts/echarts文本卡.png){ width="900px" }

### 1.4 柱状图

!!! Abstract ""
    柱状图又称条形图，是一种通过柱形的高度（横向的情况下则是宽度）来表现数据大小的一种常用图表类型，柱状图包括基础柱状图、堆叠柱状图、横向柱状图和横向堆叠柱状图，其中堆叠柱状图是柱状图的变形，不仅可以比较不同维度间总数的差别，还可以显示同类型下各数据的大小情况。  
    **注意：** 柱状图当前同一维度只能显示一种颜色。

!!! Abstract ""
    基础柱状图

    ![echarts基础柱状图](../../img/view_generation/view_gallery/ECharts/echarts基础柱状图.png){ width="900px" }

!!! Abstract ""
    堆叠柱状图

    ![echarts堆叠柱状图](../../img/view_generation/view_gallery/ECharts/echarts堆叠柱状图.png){ width="900px" }

!!! Abstract ""
    横向柱状图

    ![echarts横向柱状图](../../img/view_generation/view_gallery/ECharts/echarts横向柱状图.png){ width="900px" }

!!! Abstract ""
    横向堆叠柱状图

    ![echarts横向堆叠柱状图](../../img/view_generation/view_gallery/ECharts/echarts横向堆叠柱状图.png){ width="900px" }

### 1.5 折线图

!!! Abstract ""
	折线图是用折线将各个数据点标志连接起来的图表，可用于直角坐标系和极坐标系上。

!!! Abstract ""
    基础折线图

    ![echarts基础折线图](../../img/view_generation/view_gallery/ECharts/echarts基础折线图.png){ width="900px" }

!!! Abstract ""
    堆叠折线图

    ![echarts堆叠折现图](../../img/view_generation/view_gallery/ECharts/echarts堆叠折线图.png){ width="900px" }

### 1.6 组合图

!!! Abstract ""
    组合图由基础柱状图，基础折线图和散点图相互搭配成。

!!! Abstract ""

    ![echarts组合图](../../img/view_generation/view_gallery/ECharts/echarts组合图.png){ width="900px" }

### 1.7 散点图

!!! Abstract ""
    散点图又称 XY 散点图，将数据以点的形式展现，以显示变量间的相互关系或者影响程度，点的位置由变量的数值决定。

!!! Abstract ""
    基础散点图

    ![](../../img/view_generation/view_gallery/ECharts/echarts基础散点图.png){ width="900px" }

!!! Abstract ""
    气泡图

    ![echarts散点图](../../img/view_generation/view_gallery/ECharts/echarts散点图.png){ width="900px" }

### 1.8 雷达图

!!! Abstract ""
    雷达图又称蜘蛛网图，将多个维度的数据量映射到起始于同一个圆心的坐标轴上，结束于圆周边缘，然后将同一组的点使用线连接起来。

!!! Abstract ""

    ![echarts雷达图](../../img/view_generation/view_gallery/ECharts/echarts雷达图.png){ width="900px" }

### 1.9 仪表盘

!!! Abstract ""
    仪表盘像一个钟表或者可读盘，有刻度和指针，其中刻度表示度量，指针表示维度，指针角度表示数值，指针指向当前数值。  
    **提示：** 仪表盘当前不支持跳转设置。

!!! Abstract ""

    ![echarts仪表盘](../../img/view_generation/view_gallery/ECharts/echarts仪表盘.png){ width="900px" }

!!! Abstract ""
    **DataEase 1.9.0 版本，仪表盘支持分段显示颜色：**  
    设置位置：高级-阈值，该功能决定仪表盘区间颜色，为空则不开启阈值，范围（0-100），仅限整数，且逐级递增。  
    以下图为示例，输入 30，70；表示分 3 段，分别为[0,30]，(30,70]，(70,100]。

    ![echarts仪表盘阈值](../../img/view_generation/view_gallery/ECharts/echarts仪表盘阈值.png){ width="900px" }

### 1.10 饼图

!!! Abstract ""
    饼图以饼状图形显示一个数据系列中各项的大小与各项总和的比例，也称作扇形统计图。

!!! Abstract ""
    基础饼图

    ![echarts基础饼图](../../img/view_generation/view_gallery/ECharts/echarts基础饼图.png){ width="900px" }

!!! Abstract ""
    环形饼图

    ![echarts环形饼图](../../img/view_generation/view_gallery/ECharts/echarts环形饼图.png){ width="900px" }

### 1.11 南丁格尔玫瑰图

!!! Abstract ""
    南丁格尔玫瑰图又称鸡冠花图、极坐标区域图，是由弗罗伦斯·南丁格尔所发明，其实是一种圆形的直方图，以圆弧的半径长短表示数据的大小。

!!! Abstract ""

    ![echarts南丁格尔玫瑰图](../../img/view_generation/view_gallery/ECharts/echarts南丁格尔玫瑰图.png){ width="900px" }

### 1.12 漏斗图

!!! Abstract ""
    楼斗图由多个梯形从上而下叠加而成，从上到下的项有逻辑上的顺序关系，梯形面积表示某个业务量与上一个环节之间的差异。

!!! Abstract ""

    ![echarts漏斗图](../../img/view_generation/view_gallery/ECharts/echarts漏斗图.png){ width="900px" }

### 1.13 矩形树图

!!! Abstract ""
    矩形树图是一种常见的表达『层级数据』『树状数据』的可视化形式。它主要用面积的方式，便于突出展现出『树』的各层级中重要的节点。

!!! Abstract ""

    ![echarts矩形树图](../../img/view_generation/view_gallery/ECharts/echarts矩形树图.png){ width="900px" }

### 1.14 地图

!!! Abstract ""
    

!!! Abstract ""
    普通地图：用颜色的深浅来展示区域范围的数值大小。

    ![普通地图](../../img/view_generation/view_gallery/ECharts/echarts普通地图.png){ width="900px" }

!!! Abstract ""
    气泡地图：用气泡的大小来展示区域范围的数值大小。

    ![气泡地图](../../img/view_generation/view_gallery/ECharts/echarts气泡地图.png){ width="900px" }

## 2 AntV 图库

!!! Abstract ""
    AntV 图库是蚂蚁集团可视化团队下一款开源的图表库。

### 2.1 表格

!!! Abstract ""
    表格是数据的详情罗列，能看到明细信息，AntV 图库表格包含汇总表、明细表和透视表。  
    AntV 的表格支持更详细的表格配置，支持表头、表格对齐（左对齐、居中、右对齐），支持列宽调整，比如自适应和自定义。

!!! Abstract ""
    明细表格
    
    ![antv明细表格](../../img/view_generation/view_gallery/AntV/antv明细表.png){ width="900px" }

!!! Abstract ""
    汇总表格

    ![antv汇总表格](../../img/view_generation/view_gallery/AntV/antv汇总表.png){ width="900px" }

!!! Abstract ""
    透视表

    ![antv透视表](../../img/view_generation/view_gallery/AntV/antv透视表.png){ width="900px" }

!!! Abstract ""
    **DataEase 1.9.0 版本，透视表支持小计合计，小计会针对每层维度进行计算，总计对行或列全部数据进行计算。**

!!! Abstract ""

    ![antv透视表_小计合计](../../img/view_generation/view_gallery/AntV/antv透视表_小计合计.png){ width="900px" }  
    ![antv透视表_小计合计设置](../../img/view_generation/view_gallery/AntV/antv透视表_小计合计设置.png){ width="900px" }

### 2.2 指标卡

!!! Abstract ""
    通过文字、数字和符号的合理排版，对数据进行一目了然的展示。指标卡由看板标签和看板指标组成，标签由数据的维度决定，指标由数据的度量决定。  
    **提示：** 指标卡当前不支持跳转设置。

!!! Abstract ""

    ![antv指标卡](../../img/view_generation/view_gallery/AntV/antv指标卡.png){ width="900px" }

### 2.3 文本卡

!!! Abstract ""
    展示文本字段的实际文字可使用文本卡，文本卡可展示该字段原本的内容、时间、文本信息等。  
    **提示：** 文本卡拖入的字段必须是“维度”类型。

!!! Abstract ""
    
    ![antv](../../img/view_generation/view_gallery/AntV/antv文本卡.png){ width="900px" }

### 2.4 柱状图

!!! Abstract ""
    柱状图又称条形图，是一种通过柱形的高度（横向的情况下则是宽度）来表现数据大小的一种常用图表类型，柱状图包括基础柱状图、堆叠柱状图、横向柱状图和横向堆叠柱状图，其中堆叠柱状图是柱状图的变形，不仅可以比较不同维度间总数的差别，还可以显示同类型下各数据的大小情况。

!!! Abstract ""
    基础柱状图

    ![antv基础柱状图](../../img/view_generation/view_gallery/AntV/antv基础柱状图.png){ width="900px" }

!!! Abstract ""
    堆叠柱状图

    ![antv堆叠柱状图](../../img/view_generation/view_gallery/AntV/antv堆叠柱状图.png){ width="900px" }

!!! Abstract ""
    横向柱状图

    ![antv横向柱状图](../../img/view_generation/view_gallery/AntV/antv横向柱状图.png){ width="900px" }

!!! Abstract ""
    横向堆叠柱状图

    ![antv横向堆叠柱状图](../../img/view_generation/view_gallery/AntV/antv横向堆叠柱状图.png){ width="900px" }

### 2.5 折线图

!!! Abstract ""
    折线图是用折线将各个数据点标志连接起来的图表，可用于直角坐标系和极坐标系上。

!!! Abstract ""
    基础折线图

    ![antv基础折线图](../../img/view_generation/view_gallery/AntV/antv基础折线图.png){ width="900px" }

!!! Abstract ""
    堆叠折线图

    ![antv堆叠折线图](../../img/view_generation/view_gallery/AntV/antv堆叠折线图.png){ width="900px" }

### 2.6 散点图

!!! Abstract ""
    散点图又称 XY 散点图，将数据以点的形式展现，以显示变量间的相互关系或者影响程度，点的位置由变量的数值决定。

!!! Abstract ""
    基础散点图

    ![antv散点图](../../img/view_generation/view_gallery/AntV/antv散点图.png){ width="900px" }

!!! Abstract ""
    气泡图

    ![antv气泡图](../../img/view_generation/view_gallery/AntV/antv气泡图.png){ width="900px" }

### 2.7 雷达图

!!! Abstract ""
    雷达图又称蜘蛛网图，将多个维度的数据量映射到起始于同一个圆心的坐标轴上，结束于圆周边缘，然后将同一组的点使用线连接起来。

!!! Abstract ""

    ![antv雷达图](../../img/view_generation/view_gallery/AntV/antv雷达图.png){ width="900px" }

### 2.8 仪表盘

!!! Abstract ""
    像一个钟表或者可读盘，有刻度和指针，其中刻度表示度量，指针表示维度，指针角度表示数值，指针指向当前数值。  
    **提示：** 仪表盘当前不支持跳转设置。

!!! Abstract ""

    ![antv仪表盘](../../img/view_generation/view_gallery/AntV/antv仪表盘.png){ width="900px" }

!!! Abstract ""
    **DataEase 1.9.0 版本，仪表盘支持分段显示颜色：**  
    设置位置：高级-阈值，该功能决定仪表盘区间颜色，为空则不开启阈值，范围（0-100），仅限整数，且逐级递增。  
    以下图为示例，输入 30，70；表示分 3 段，分别为[0,30]，(30,70]，(70,100]。

    ![antv仪表盘](../../img/view_generation/view_gallery/AntV/antv仪表盘阈值.png){ width="900px" }

### 2.9 饼图

!!! Abstract ""
    饼图以饼状图形显示一个数据系列中各项的大小与各项总和的比例，也称作扇形统计图。

!!! Abstract ""
    基础饼图

    ![antv基础饼图](../../img/view_generation/view_gallery/AntV/antv基础饼图.png){ width="900px" }

!!! Abstract ""
    环形饼图

    ![antv环形饼图](../../img/view_generation/view_gallery/AntV/antv环形饼图.png){ width="900px" }

### 2.10 南丁格尔玫瑰

!!! Abstract ""
    南丁格尔玫瑰图又称鸡冠花图、极坐标区域图，是由弗罗伦斯·南丁格尔所发明，其实是一种圆形的直方图，以圆弧的半径长短表示数据的大小。

!!! Abstract ""

    ![antv南丁格尔玫瑰图](../../img/view_generation/view_gallery/AntV/antv南丁格尔玫瑰图.png){ width="900px" }

### 2.11 漏斗图

!!! Abstract ""
	楼斗图由多个梯形从上而下叠加而成。从上到下的项有逻辑上的顺序关系，梯形面积表示某个业务量与上一个环节之间的差异。

!!! Abstract ""

    ![antv漏斗图](../../img/view_generation/view_gallery/AntV/antv漏斗图.png){ width="900px" }

### 2.12 矩形树图

!!! Abstract ""
    矩形树图是一种常见的表达『层级数据』『树状数据』的可视化形式。它主要用面积的方式，便于突出展现出『树』的各层级中重要的节点。

!!! Abstract ""

    ![antv矩形树图](../../img/view_generation/view_gallery/AntV/antv矩形树图.png){ width="900px" }

### 2.13 瀑布图

!!! Abstract ""
    瀑布图采用绝对值与相对值结合的方式，适用于表达数个特定数值之间的数量变化关系，因图形形似瀑布流水所以称之为瀑布图。

!!! Abstract ""

    ![antv瀑布图](../../img/view_generation/view_gallery/AntV/antv瀑布图.png){ width="900px" }

### 2.14 水波图

!!! Abstract ""
    水波图的水波高度表示指标值，当水填满或溢出时，代表指标值已经到达目标值。  
    **提示：** 水波图当前不支持跳转设置。

!!! Abstract ""

    ![antv水波图](../../img/view_generation/view_gallery/AntV/antv水波图.png){ width="900px" }

### 2.15 词云图

!!! Abstract ""
	词云图又称文字云，是文本数据的视觉表示，由词汇组成类似云的彩色图形，用于展示大量文本数据。每个词的重要性以字体大小或颜色显示。  
    **提示：** 词云图当前不支持跳转设置。

!!! Abstract ""

    ![antv词云图](../../img/view_generation/view_gallery/AntV/词云图.png){ width="900px" }