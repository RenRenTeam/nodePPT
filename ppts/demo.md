title:  个人简历
speaker: 周恒毅
url: https://github.com/ksky521/nodePPT
transition: move
files: [/js/demo.js,/css/demo.css,/js/zoom.js]
theme: moon
usemathjax: yes
[slide data-transition="zoomin"  style="background-image:url('/5.jpg')"]
    <style>
        
    </style>
<div class="vertical">
    <div class="main-header-content inner">
        <h1 class="page-title">前端路 - Henry.Zhou</h1>
        <h3 class="page-description"><span class="icon-arrow-left2"></span> 请使用方向键交互 <span class="icon-arrow-right2"></span></h2>
    </div>
</div>
[slide data-transition="zoomin" style="background-image:url('/header.jpg')"]

## 精通 .net 相关技术 熟悉架构分析与设计
    <div style="float:rigtht; font-size:18px; width:100%;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;专治线上疑难杂症的Bug克星 </div> <br/>
### 目前框架技术使用.net 份额不到30% 
### JavaScript全栈框架很多，各利弊也清楚.
### 在推崇模块化的前端里，个人更偏向于根据自身需求选择模块订制（angular.js/backbone.js/react.js/flux.js）
### 使用 Python 编写脚本抓数据和其他服务处理
### 项目中使用Solr提供分词及搜索服务
### Windows Server IIS / Apache / Nginx
<br />
<small>
热爱Coding，喜欢尝试新技术和总结，乐在分享给他人和开源。
<br />
前端导航 http://get-set.cn/front-end-collect/。</small>
<br />

[slide data-transition="glue" style="background-image:url('/img/bg1.png')""]
# 2010、10 - 2012、7 {:&.flexbox.vcenter}
## 上海珍岛信息技术有限公司
（150-500人、民营公司） [ 1年9个月] 软件工程师
## 参与项目
* 官网：http://www.trueland.net
* 企业网站开发
* 公司ERP
* 物流平台的功能维护 http://www.02156.cn

## 业余作品
* Socket 远程屏幕监控：
<a href="http://www.51aspx.com/code/RemoteMonitor" target="_blank">51aspx</a>
<a href="https://github.com/RenRenTeam/RemoteMonitor" target="_blank">github</a>

* 多线程文件备份-IT部门需求：
<a href="http://www.51aspx.com/code/codename/3203" target="_blank">51aspx</a>
<a href="https://github.com/RenRenTeam/BackupsTools" target="_blank">github</a>

* 代码生成器：简单3层框架

* Sqlserver 存储过程生成器：
<a href="https://github.com/ZhouHengYi/ProcGenerator" >github</a>
<p id="incallback" style="font-size:16px;">自我总结：从表设计到功能独立开发完成，效率高，动手能力强。
目标 1天内完成企业站的程序开发</p>

[slide data-transition="glue" style="background-image:url('/img/bg1.png')"]
# 2012、7 - 2014、3 {:&.flexbox.vcenter}
## 新蛋信息技术（上海）有限公司
（500-1000人、外资(欧美)） [ 1年7个月] 高级软件工程师
## 参与项目
<div>
<table style="border:0px;background-color:#b2d7dd">
    <tr>
        <td>
            <div style="background:url('/cmb.png');width:232px;height:46px;cursor:pointer;background-repeat: no-repeat;padding-left:252px;" title="http://mall.cmbchina.com/" onclick="window.open('http://mall.cmbchina.com/')">&nbsp;</div>
        </td>
        <td>
            <div style="background:url('/xjhlogo.png');width:232px;height:55px;cursor:pointer;background-repeat: no-repeat;padding-left:252px;" title="http://www.xjh.com/" onclick="window.open('http://www.xjh.com/')">&nbsp;</div>
        </td>
    </tr>
    <tr>
        <td>
        <div style="padding-bootom:100px;background:url('/cmb2.png');width:232px;height:46px;cursor:pointer;background-repeat: no-repeat;padding-left:252px;" title="http://jf.cmbchina.com/" onclick="window.open('http://jf.cmbchina.com/')">&nbsp;</div>
        </td>
        <td>
            <div style="background:url('/ellelogo.jpg');width:232px;height:80px;cursor:pointer;background-repeat: no-repeat;padding-left:382px;" title="http://jwww.elleshop.com.cn/" onclick="window.open('http://www.elleshop.com.cn')">&nbsp;</div>
        </td>
    </tr>
</table>

## 业余作品
* 代码生成器：
<a href="https://github.com/RenRenTeam/CodeGenerator" target="_blank">Assembly版和WCF版</a>
``` 
Page -> Facade -> Restfule -> ISqlDataAccess -> SqlDataAccess -> command -> DB
```
* .net分布式框架：
<a href="https://github.com/ZhouHengYi/HFramework" >github</a>

<pre><code class="markdown hljs ">从表设计到功能独立开发完成，效率高，动手能力强。
自我目标 1天内完成企业站的程序开发
</code></pre>

[slide]
# Asp.net 
* 理解组件与页面生命周期
* 系统相关配置(web.config)
* 网站部署与发布IIS常见错误处理
* 能够快速定位出现的程序问题
* DataEntity 表与实体类之间映射实现原理
* WCF-WebAPI | WCF-Restful 使用与相关设计
* 其他相关服务（UploadService / MailService）
* AjaxPro / NPOI / MySql / SqlServer / PostSharp

[slide]
#架构设计：
* 基于WCF-Restful实现客户端与服务端分离
* 不同环境的切换配置
```
<!-- 设置网站启动时和网站关闭时自动执行的任务的配置文件路径， 支持绝对路径或相对于WebHost跟目录的路径-->
    <add key="AutorunConfigPath" value="Configuration\Autorun.config"/>
    <!-- 文件监控配置 -->
    <add key="FileWatcherConfigPath" value="Configuration\FileWatcher.config"/>
    <!-- ProjectName：项目名称
           InteractionKey：加密字符串
           客户端与REST服务端进行交互时加密匹配 -->
    <add key="ProjectName" value="HO"/>
    <add key="InteractionKey" value="Henry"/>
    <!-- Cookie过期时间 -->
    <add key="CookieTimeOut" value="604800"/>
    <!-- Rest返回类型 -->
    <add key="RestResponseFormat" value="application/json"/>
    <!-- Rest 服务地址 -->
    <add key="RestServiceHost" value="http://localhost:8816/"/>
    <add key="RestServiceHost_Report" value="http://rest.elleshop.com.cn"/>
    <!-- 图片上传服务路径 -->
    <add key="UploadService" value="http://localhost:8317/Upload.aspx"/>
    <add key="EditorUploadService" value="http://localhost:8317/upload_json.ashx"/>
    <!-- 图片地址 -->
    <add key="UploadImageUrl" value="http://localhost:8317/Images/"/>
    <!-- 是否隐藏程序错误异常 True | False-->
    <add key="HandlerError" value="False"/>
    <!-- 页面路径配置 -->
    <add key="PageConfigPath" value="Configuration\Page\Page.config"/>
    <!-- 导航路径配置 -->
    <add key="SiteMapConfigPath" value="Configuration\Page\SiteMap.config"/>
    <!-- 路由配置 -->
    <add key="UrlMapping" value="Configuration\Page\UrlMapping.config"/>
```
[slide]
* 动态分配访问数据库，目前支持3种类型 sqlserver |  oledb  | mysql
* 系统日志记录 ，方式包括：
```
<log globalRegionName="H.Service.IISHost" localRegionName="H.Service.IISHost">
<webservice param="LogService/CreateLog" />
<!-- 日志文本记录地址，默认不写的情况不记录日志-->
<text param="D:/CenterLog/H.Service.IISHost"/>
</log>
* 反向代理：Nginx
* 消息队列：SQL Server Service Borker(SSB)
* 搜索引擎：Apache Solr

<br/>
商品搜索使用 分词、同义词、停词

<br/>
* <a href="https://github.com/ZhouHengYi/HFramework" target="_blank">源代码</a>
    <a href="https://github.com/ZhouHengYi/HFramework/blob/master/HFramework.doc">HFramework.doc - 框架说明</a>
[slide]
    <style>
        .testimonial-container .spencer {
    background: url(http://zurb.com/university/assets/university/spencer-cd79fcad1f9ce7306f9d053dccb154e6.png) no-repeat 3% bottom;
    background-size: auto 424px;
}
universitymedia="screen"
.row {
    width: 100%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 0;
    margin-bottom: 0;
    max-width: 62.5em;
}
.testimonial-container .testimonial {
    padding-left: 320px;
    height:100%;
}
universitymedia="screen"
.bump-xl {
    margin-top: 90px;
}
media="screen"
@media only screen and (min-width: 768px)
.large-12 {
    position: relative;
    width: 100%;
}
universitymedia="screen"
@media only screen
.column, .columns {
    position: relative;
    padding-left: 0.9375em;
    padding-right: 0.9375em;
    float: left;
}
universitymedia="screen"
.column, .columns {
    position: relative;
    padding-left: 0.9375em;
    padding-right: 0.9375em;
    width: 100%;
    float: left;
}
universitymedia="screen"
div, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, p, blockquote, th, td {
    margin: 0;
    padding: 0;
    direction: ltr;
}
universitymedia="screen"
*, *:before, *:after {
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
    </style>
<div class="testimonial-container">
<div class="row spencer">
<div class="large-12 columns">
<div class="testimonial bump-xl">
<p class="test-quote">工作态度、环境适应技术实力、</p>
    <p>目前就职：<a href="http://new.rrliuxue.com" title="互联网留学单向收费发起者" target="_target"> 人人留学 </a> </p>
<p>技术总监 </p>
    <p>cto@rrliuxue.com | 262767665@qq.com</p>
</div>
</div>
</div>
</div>


----
