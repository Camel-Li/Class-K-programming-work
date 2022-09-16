软工K班个人编程作业

作业进度

9月10日：数据爬取工作完成，爬取内容从2021年今天到2022年今天，测试excel文件只爬取最近24天的数据（卫健委第一页所有链接数据）

9月11日：将数据分类存放到excel表中，已经实现，按照一天所有省份信息为一个文件，和按照不同时间疫情变化为另一个文件

9月12日：学习flask和echarts等web渲染，初步掌握，从网站上寻找出合适的HTML5网页模板和Apache ECharts模板，作为可视化的展示模板。

9月13日：学习excel数据转sqlite数据库文件，一直有bug搞不懂。随后直接使用前几日保存的excel数据作为可视化的数据源。目前以实现excel表中数据成功接入HTML5，并使用flask和boostrap等成功渲染一个大表格，采用斑马线格式和数据高亮等等。 

9月15日：通过几天的努力，目前基本的作业已经完成，实现数据的爬取分析可视化，除了用到的python库函数以外，还有主程序Corona_Virus_Spider.py文件，py生成的excel文件，控制web服务端生成的app.py文件，HTML5网页（可视化界面），以及网页用到的js，css和素材图片。程序采用python爬取和分析数据，存储数据到excel文件，用flask的web框架实现Werkzeug路由转发和Jinja2模板渲染，构建网页，使用Echarts做图表可视化。最终以比较简单的方式实现了目标。至此，软工K班个人编程作业大体完成。
