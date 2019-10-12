<style>
body{
    margin: 0 auto;
    font-family: "Microsoft YaHei", arial,sans-serif;
    color: #444444;
    line-height: 1;
    padding: 30px;
}
@media screen and (min-width: 768px) {
    body {
        width: 748px;
        margin: 10px auto;
    }
}
h1, h2, h3, h4 {
    color: #111111;
    font-weight: 400;
    margin-top: 1em;
}

h1, h2, h3, h4, h5 {
	font-family: Georgia, Palatino, serif;
}
h1, h2, h3, h4, h5, p , dl{
    margin-bottom: 16px;
    padding: 0;
}
h1 {
    font-size: 48px;
    line-height: 54px;
}
h2 {
    font-size: 36px;
    line-height: 42px;
}
h1, h2 {
    border-bottom: 1px solid #EFEAEA;
    padding-bottom: 10px;
}
h3 {
    font-size: 24px;
    line-height: 30px;
}
h4 {
    font-size: 21px;
    line-height: 26px;
}
h5 {
    font-size: 18px;
    list-style: 23px;
}
a {
    color: #0099ff;
    margin: 0;
    padding: 0;
    vertical-align: baseline;
}
a:hover {
    text-decoration: none;
    color: #ff6600;
}
a:visited {
    /*color: purple;*/
}
ul, ol {
    padding: 0;
    padding-left: 24px;
    margin: 0;
}
li {
    line-height: 24px;
}
p, ul, ol {
    font-size: 16px;
    line-height: 24px;
}

ol ol, ul ol {
    list-style-type: lower-roman;
}

/*pre {
    padding: 0px 24px;
    max-width: 800px;
    white-space: pre-wrap;
}
code {
    font-family: Consolas, Monaco, Andale Mono, monospace;
    line-height: 1.5;
    font-size: 13px;
}*/

code, pre {
    border-radius: 3px;
    background-color:#f7f7f7;
    color: inherit;
}

code {
    font-family: Consolas, Monaco, Andale Mono, monospace;
    margin: 0 2px;
}

pre {
    line-height: 1.7em;
    overflow: auto;
    padding: 6px 10px;
    border-left: 5px solid #6CE26C;
}

pre > code {
    border: 0;
    display: inline;
    max-width: initial;
    padding: 0;
    margin: 0;
    overflow: initial;
    line-height: inherit;
    font-size: .85em;
    white-space: pre;
    background: 0 0;

}

code {
    color: #666555;
}


/** markdown preview plus 对于代码块的处理有些问题, 所以使用统一的颜色 */
/*code .keyword {
  color: #8959a8;
}

code .number {
  color: #f5871f;
}

code .comment {
  color: #998
}*/

aside {
    display: block;
    float: right;
    width: 390px;
}
blockquote {
    border-left:.5em solid #eee;
    padding: 0 0 0 2em;
    margin-left:0;
}
blockquote  cite {
    font-size:14px;
    line-height:20px;
    color:#bfbfbf;
}
blockquote cite:before {
    content: '\2014 \00A0';
}

blockquote p {
    color: #666;
}
hr {
    text-align: left;
    color: #999;
    height: 2px;
    padding: 0;
    margin: 16px 0;
    background-color: #e7e7e7;
    border: 0 none;
}

dl {
    padding: 0;
}

dl dt {
    padding: 10px 0;
    margin-top: 16px;
    font-size: 1em;
    font-style: italic;
    font-weight: bold;
}

dl dd {
    padding: 0 16px;
    margin-bottom: 16px;
}

dd {
    margin-left: 0;
}

/* Code below this line is copyright Twitter Inc. */

button,
input,
select,
textarea {
    font-size: 100%;
    margin: 0;
    vertical-align: baseline;
    *vertical-align: middle;
}
button, input {
    line-height: normal;
    *overflow: visible;
}
button::-moz-focus-inner, input::-moz-focus-inner {
    border: 0;
    padding: 0;
}
button,
input[type="button"],
input[type="reset"],
input[type="submit"] {
    cursor: pointer;
    -webkit-appearance: button;
}
input[type=checkbox], input[type=radio] {
    cursor: pointer;
}
/* override default chrome & firefox settings */
input:not([type="image"]), textarea {
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
}

input[type="search"] {
    -webkit-appearance: textfield;
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
}
input[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none;
}
label,
input,
select,
textarea {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 13px;
    font-weight: normal;
    line-height: normal;
    margin-bottom: 18px;
}
input[type=checkbox], input[type=radio] {
    cursor: pointer;
    margin-bottom: 0;
}
input[type=text],
input[type=password],
textarea,
select {
    display: inline-block;
    width: 210px;
    padding: 4px;
    font-size: 13px;
    font-weight: normal;
    line-height: 18px;
    height: 18px;
    color: #808080;
    border: 1px solid #ccc;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px;
}
select, input[type=file] {
    height: 27px;
    line-height: 27px;
}
textarea {
    height: auto;
}
/* grey out placeholders */
:-moz-placeholder {
    color: #bfbfbf;
}
::-webkit-input-placeholder {
    color: #bfbfbf;
}
input[type=text],
input[type=password],
select,
textarea {
    -webkit-transition: border linear 0.2s, box-shadow linear 0.2s;
    -moz-transition: border linear 0.2s, box-shadow linear 0.2s;
    transition: border linear 0.2s, box-shadow linear 0.2s;
    -webkit-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
    -moz-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
    box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1);
}
input[type=text]:focus, input[type=password]:focus, textarea:focus {
    outline: none;
    border-color: rgba(82, 168, 236, 0.8);
    -webkit-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
    -moz-box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
    box-shadow: inset 0 1px 3px rgba(0, 0, 0, 0.1), 0 0 8px rgba(82, 168, 236, 0.6);
}
/* buttons */
button {
    display: inline-block;
    padding: 4px 14px;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 13px;
    line-height: 18px;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
    -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05);
    background-color: #0064cd;
    background-repeat: repeat-x;
    background-image: -khtml-gradient(linear, left top, left bottom, from(#049cdb), to(#0064cd));
    background-image: -moz-linear-gradient(top, #049cdb, #0064cd);
    background-image: -ms-linear-gradient(top, #049cdb, #0064cd);
    background-image: -webkit-gradient(linear, left top, left bottom, color-stop(0%, #049cdb), color-stop(100%, #0064cd));
    background-image: -webkit-linear-gradient(top, #049cdb, #0064cd);
    background-image: -o-linear-gradient(top, #049cdb, #0064cd);
    background-image: linear-gradient(top, #049cdb, #0064cd);
    color: #fff;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
    border: 1px solid #004b9a;
    border-bottom-color: #003f81;
    -webkit-transition: 0.1s linear all;
    -moz-transition: 0.1s linear all;
    transition: 0.1s linear all;
    border-color: #0064cd #0064cd #003f81;
    border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25);
}
button:hover {
    color: #fff;
    background-position: 0 -15px;
    text-decoration: none;
}
button:active {
    -webkit-box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
    -moz-box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
    box-shadow: inset 0 3px 7px rgba(0, 0, 0, 0.15), 0 1px 2px rgba(0, 0, 0, 0.05);
}
button::-moz-focus-inner {
    padding: 0;
    border: 0;
}
table {
    *border-collapse: collapse; /* IE7 and lower */
    border-spacing: 0;
    width: 100%;
}
table {
    border: solid #ccc 1px;
    -moz-border-radius: 6px;
    -webkit-border-radius: 6px;
    border-radius: 6px;
    /*-webkit-box-shadow: 0 1px 1px #ccc;
    -moz-box-shadow: 0 1px 1px #ccc;
    box-shadow: 0 1px 1px #ccc;   */
}
table tr:hover {
    background: #fbf8e9;
    -o-transition: all 0.1s ease-in-out;
    -webkit-transition: all 0.1s ease-in-out;
    -moz-transition: all 0.1s ease-in-out;
    -ms-transition: all 0.1s ease-in-out;
    transition: all 0.1s ease-in-out;
}
table td, .table th {
    border-left: 1px solid #ccc;
    border-top: 1px solid #ccc;
    padding: 10px;
    text-align: left;
}

table th {
    background-color: #dce9f9;
    background-image: -webkit-gradient(linear, left top, left bottom, from(#ebf3fc), to(#dce9f9));
    background-image: -webkit-linear-gradient(top, #ebf3fc, #dce9f9);
    background-image:    -moz-linear-gradient(top, #ebf3fc, #dce9f9);
    background-image:     -ms-linear-gradient(top, #ebf3fc, #dce9f9);
    background-image:      -o-linear-gradient(top, #ebf3fc, #dce9f9);
    background-image:         linear-gradient(top, #ebf3fc, #dce9f9);
    /*-webkit-box-shadow: 0 1px 0 rgba(255,255,255,.8) inset;
    -moz-box-shadow:0 1px 0 rgba(255,255,255,.8) inset;
    box-shadow: 0 1px 0 rgba(255,255,255,.8) inset;*/
    border-top: none;
    text-shadow: 0 1px 0 rgba(255,255,255,.5);
    padding: 5px;
}

table td:first-child, table th:first-child {
    border-left: none;
}

table th:first-child {
    -moz-border-radius: 6px 0 0 0;
    -webkit-border-radius: 6px 0 0 0;
    border-radius: 6px 0 0 0;
}
table th:last-child {
    -moz-border-radius: 0 6px 0 0;
    -webkit-border-radius: 0 6px 0 0;
    border-radius: 0 6px 0 0;
}
table th:only-child{
    -moz-border-radius: 6px 6px 0 0;
    -webkit-border-radius: 6px 6px 0 0;
    border-radius: 6px 6px 0 0;
}
table tr:last-child td:first-child {
    -moz-border-radius: 0 0 0 6px;
    -webkit-border-radius: 0 0 0 6px;
    border-radius: 0 0 0 6px;
}
table tr:last-child td:last-child {
    -moz-border-radius: 0 0 6px 0;
    -webkit-border-radius: 0 0 6px 0;
    border-radius: 0 0 6px 0;
}
</style>
<title>受电弓安全状态检测系统说明文档</title>

# 受电弓安全状态检测系统说明文档

西安恒景通视觉科技有限责任公司

2019年10月

## 1. 公司简介

**西安恒景通视觉科技有限公司**是一家以互联网为载体，面向全国，提供人工智能与计算机视觉软硬件综合服务平台的高科技研发公司。公司现有研发人员70余人，具有较强的科研开发能力，特别是在智能图像信息处理软件领域具有独特的开发能力。科研领军人物是4名具有英美留学背景的海归博士。公司拥有一批高素质、专业化的博士后、博士、硕士研究生人才队伍，本着一流的服务意识，客户之上、用户第一的宗旨，竭诚为客户服务。
**受电弓安全状态检测产品由西安恒景通视觉科技有限公司与西安交通大学科研团队联合开发**，经过近年来的用户测试与验证，产品应用在国内多家科研院所与企业，并获得广泛好评，是目前世界上最先进的受电弓安全状态检测实时处理解决方案。

## 2. 受电弓安全状态检测原理

受电弓安全状态检测是基于大数据与深度学习的人工智能算法，实现对受电弓安全状态的准确检测。本产品采用多年项目积累收集到的超过800G视频数据，并对视频数据进行整理、预处理和分析，实现对20多万张数据的标注和训练，得到最优的算法模型。
本产品提出的基于深度学习目标识别的方法分为三个阶段：首先在给定的图像上选择一些候选的区域，然后对这些区域提取特征，最后使用训练的分类器进行分类。下面对这三个阶段分别进行介绍。

1) 区域选择
这一步是为了对目标的位置进行定位。由于目标可能出现在图像的任何位置，而且目标的大小、长宽比例也不确定，所以采用滑动窗口的策略对整幅图像进行遍历，而且通过设置不同的尺度，不同的长宽比，可以包含目标所有可能出现的位置。
2) 特征提取
由于目标的形态多样性，光照变化多样性，背景多样性等因素使得设计一个鲁棒的特征并不是那么容易。然而提取特征的好坏直接影响到分类的准确性，本产品采用具有不变特性的结构化特征。
3) 分类器
本产品研究了结合深度学习和稀疏编码，解决了目标的识别与检测问题，采用多级分类器结构，提出一种基于迁移自学习的目标快速识别分类方法。

![图1. 深度学习目标识别模型](./受电弓产品说明文档.files/受电弓产品说明文档868.png)

本产品的深度学习模型如图1所示，将目标识别与检测任务转换成一个回归问题，大大加快检测的速度，使得网络模型可以实时处理视频图像。不仅利用高层特征的语义信息，还考虑了低层特征的细节纹理信息，使得目标检测定位更为精准。

## 3. 受电弓安全状态检测产品简介

高铁受电弓实时智能监测与预警功能如图2-3所示。

![图2. 高铁受电弓监控画面](./受电弓产品说明文档.files/受电弓产品说明文档1035.png)

![图3. 高铁受电弓火花智能检测](./受电弓产品说明文档.files/受电弓产品说明文档1052.png)

![图4. 高铁受电弓火花智能检测与查询](./受电弓产品说明文档.files/受电弓产品说明文档1076.png)

点击主界面“图片查询”按钮即可进行图片查询。询时点击左侧选择开始时间和结束时间并点击“查询”按钮即可进行图片查询。

## 4. 测试视频
以下是测试视频

<p align="center">
<video width="320" height="240" controls="controls" style="text-align:center">
  <source src="./1.mp4" type="video/mp4" />
</video></br>
<video width="320" height="240" controls="controls"style="text-align:center">
  <source src="2.mp4" type="video/mp4" />
</video></br>
<video width="320" height="240" controls="controls" style="text-align:center">
  <source src="3.mp4" type="video/mp4" />
</video></br>
</p>
