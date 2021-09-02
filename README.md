
<div align='center' >
  <body>
    <h1 style="color:red;font-size:40px;">项目结题报告写作标准</h1>
    <h4 style="color:blue;font-size:18px;">中科生信技术部</h4>
  </body>
</div>

<p align="center">
  <a href="https://github.com/Carthage/Carthage/"><img src="https://img.shields.io/badge/zhongkeshengxin-v1.0.0-4BC51D.svg?style=flat"></a>
<!---
<a href="https://travis-ci.org/onevcat/Kingfisher"><img src="https://img.shields.io/travis/onevcat/Kingfisher/master.svg"></a>
<a href="https://swift.org/package-manager/"><img src="https://img.shields.io/badge/SPM-ready-orange.svg"></a>
<a href="http://onevcat.github.io/Kingfisher/"><img src="https://img.shields.io/cocoapods/v/Kingfisher.svg?style=flat"></a>
<a href="https://raw.githubusercontent.com/onevcat/Kingfisher/master/LICENSE"><img src="https://img.shields.io/cocoapods/l/Kingfisher.svg?style=flat"></a>
<a href="http://onevcat.github.io/Kingfisher/"><img src="https://img.shields.io/cocoapods/p/Kingfisher.svg?style=flat"></a>
<a href="https://codebeat.co/projects/github-com-onevcat-kingfisher"><img alt="codebeat badge" src="https://codebeat.co/assets/svg/badges/A-398b39-669406e9e1b136187b91af587d4092b0160370f271f66a651f444b990c2730e9.svg" /></a>
--->
</p>

## 0 报告排版
报告排版问题参考Teambition上的“项目交付报告模板.docx”，具体下载方式如下：

![image](https://user-images.githubusercontent.com/86351697/131773848-4fd01341-a857-4ddd-8740-a06ea618f8eb.png)
![image](https://user-images.githubusercontent.com/86351697/131773861-349c3b68-a9f5-4161-9687-93be91144cd5.png)

![image](https://user-images.githubusercontent.com/86351697/131773869-a73268ca-c027-4c4b-a344-5e546c9971ce.png)
![image](https://user-images.githubusercontent.com/86351697/131773875-60ba072c-6ffa-403f-aca4-e7393298e644.png)

“项目交付报告模板.docx”可能会不定期更新，请大家注意一下，有更新时及时替换更新后的模板。

## 1 原始数据
1. 写清数据来源、样本数目、基因数目；
2. 是否对数据进行过清洗过滤，如果有，写清楚过滤标准及过滤后的样本和基因数目；
3. 如果有分组，写清分组标准及各组样本数目；
4. 不仅在写作中，分析之前也要注意，对于方案中提到的数据集：
    - 要注意核对各样本的取样来源是否一致，如果不一致，判断是否对分析有影响，同时也要体现在报告中；
    - 对于某些肿瘤，例如肺癌，有多种亚型，需要核对数据集中是否是同一种亚型；如果是多种亚型，判断多种亚型是否可以混合分析；如果不能混合分析需要剔除非目标亚型，以上也要体现在报告中；
    - 其他。

## 2 分析方法
1、语言描述要求逻辑清晰，没有前后矛盾、模棱两可；
2. 语言描述后添加技术路线图；

## 3 结果展示
### 3.1 表格
1. 要求三线表；
2. 不建议展示超过一页的大表，此类表格可以仅展示前10行；如确实需要展示，跨页后的表格需要添加标题行和附表提示；
3. 表格字体和正文一致，标题行加粗，全部居中；
4. 避免出现表格和表注分隔两页的情况；

示例1：

![image](https://user-images.githubusercontent.com/86351697/131794334-ea63d470-a242-4a06-ae05-67a98e472d38.png)


### 3.2 图片
1. 结果文件中每张图片包含两种格式：png和pdf；
2. 图片颜色建议选择亮色、辨识度高的颜色；
3. 尽量避免图片占一整页的情况，在不影响可读性的情况下，可以将图片适当调小；
4. 避免图片和图注分隔两页的情况。
5. 多个图片拼接：首选R包patchwork等；如果patchwork拼接后影响图片质量，可以选择线下手动方式；
6. 图片保存：首选R包Ipaper或ggsave等；如果命令保存存在问题，可以选择手动保存

示例1：

![image](https://user-images.githubusercontent.com/86351697/131794545-d1682df5-ae9d-4002-bca7-f0fa66eef51f.png)

### 3.3 内容
1. 各个分析点的分析方式、阈值选择需要描述清楚；
2. 各个分析点的结果，获取方式如果是通过筛选、交集、并集等额外的方式获得，需要着重说明；交集方式需要提供venn图；
3. 各个分析点之间的衔接需要逻辑自洽；
4. 正文语句需要逻辑通顺，没有语病和标点符号错误等写作问题。

## 4 总结
1、对整个分析的结果进行简单描述、总结，要求前后一致、逻辑自洽；

## 5 软件列表
1. 三线表，格式要求同上述表格要求；
2. 要求内容准确：包括软件名称、软件版本、软件用途。

示例（部分表格）：

![image](https://user-images.githubusercontent.com/86351697/131794638-293249a1-6f3c-45af-9c92-5cbafb58a15f.png)