
该数据可视化的最终效果图链接：[链接](http://bl.ocks.org/BangShen/raw/88fd451cf1bdc212905a3c1b464a67c5/)

## 1. 概要
这次数据可视化的数据来自于1157条棒球手的数据集，其中包括他们的用手习惯（左手，右手，双手），身高，体重以及击球率和全垒得分。探究对比不同的身体因素和习惯对成绩的影响，通过该可视化发现惯用左手的运动员的击中率相比惯用右手的运动员击中率高，惯用右手的运动员的平均得分比较分散，而惯用左手的运动员的平均得分比较集中且分值较高。
## 2. 设计
#### 1. 设计选择
本可视化项目中以运动员的用手习惯作为类别，以击球率和全垒得分作为球技的高低，同时变化研究了身高和体重与其球技之间的关系，因此通过互动按钮一共采用了四种组合图，分别是
* Height-avg
* Height-HR
* Weight-avg
* Weight-HR


## 3.反馈

1. 修改了横坐标的位置
2. 修改了不同handedness的颜色，使其三者之间区分度更加明显
3. 修改了横纵坐标的上数字镂空的渲染效果
4. 添加了横坐标和纵坐标的单位,分别给eight标明in(英寸)的单位，weight标明lb(磅)，修改纵坐标中关于HR(Home Run)和avg的说明.


## 迭代和改进
第一次绘图的绘图的结果：[链接](http://bl.ocks.org/BangShen/eb691f31e3aa5e62ef7a2de332f902bd)</br>
这个只是第一次尝试，没有添加互动按钮，也没有将不同handedness的运动员用颜色区分开




##	4.资源

* [css布局](https://www.w3schools.com/Css)
* [lengend布局](https://stackoverflow.com/questions/13573771/adding-a-chart-legend-in-d3)
* [api接口文档](https://developer.mozilla.org/zh-CN/)
* [精通D3.js交互式数据可视化高级编程](https://book.douban.com/subject/27071903/)这本书的确不错，对很多细节解释的比较清楚


#data_visualization
