# qt_2019_ncov

基于Qt/C++框架实现的新冠肺炎疫情数据可视化显示。主要包括新型冠状病毒肺炎疫情数据实时查看，确诊/疑似/治愈/死亡数据趋势折线图，各省市和海外数据树形显示，实时新闻动态显示等，数据源来自腾讯新闻接口，数据格式为JSON。

桌面PC版，项目地址https://github.com/qtexe/qt_2019_ncov

![](https://wcc-blog.oss-cn-beijing.aliyuncs.com/QtUpdate/qt_2019_ncov/qt_2019_ncov.jpg)


嵌入式Linux版，项目地址：https://github.com/qtexe/qte_2019_ncov

![](https://wcc-blog.oss-cn-beijing.aliyuncs.com/QtUpdate/qt_2019_ncov/qte_2019_ncov.jpg)


### 如何实现

我的博客文章:
- [基于Qt的新冠肺炎疫情数据实时监控平台（开源小项目）](https://www.qtexe.com/post/2020-02-14-qt-ncov/)
- [基于Qt的新冠肺炎疫情数据实时监控平台1.1版本](https://www.qtexe.com/post/2020-02-15-qt-ncov-2/)
### 版本历史

[v1.0](https://github.com/qtexe/qt_2019_ncov/releases/tag/v1.0)

- 全国疫情数据实时显示
- 历史疫情数据趋势折线图显示
- 各省市和海外疫情数据树形显示
- 最新疫情新闻动态显示
- 最新辟谣信息展示
- 手动和自动更新（每5分钟）

[v1.1](https://github.com/qtexe/qt_2019_ncov/releases/tag/v1.1)

- 添加一个API和窗口，用于显示辟谣信息详情
- 辟谣信息详情界面设计
- 打开超链接改为QtDesktop，不使用widows.h(linux不支持)

