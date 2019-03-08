
<html>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<head>
<title>mysql简介</title>
<head>
<body>
<h1>MySql(关系型数据库管理系统)</h1>
<ol>
<div>MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，目前属于 Oracle 旗下产品。MySQL 是最流行的关系型数据库管理系统之一，在 WEB 应用方面，MySQL是最好的 RDBMS (Relational Database Management System，关系数据库管理系统) 应用软件。</div>
<div>MySQL是一种关系数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。</div>
<div>MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。</div>
<div>由于其社区版的性能卓越，搭配 PHP 和 Apache 可组成良好的开发环境。</div>
</ol>
<br>
<br>
<h2>应用环境</h2>
<ol>

<div>与其他的大型数据库例如 Oracle、DB2、SQL Server等相比，MySQL 自有它的不足之处，但是这丝毫也没有减少它受欢迎的程度。对于一般的个人使用者和中小型企业来说，MySQL提供的功能已经绰绰有余，而且由于 MySQL是开放源码软件，因此可以大大降低总体拥有成本。</div>

<div>Linux作为操作系统，Apache 或Nginx作为 Web 服务器，MySQL 作为数据库，PHP/Perl/Python作为服务器端脚本解释器。由于这四个软件都是免费或开放源码软件（FLOSS)，因此使用这种方式不用花一分钱（除开人工成本）就可以建立起一个稳定、免费的网站系统，被业界称为“LAMP“或“LNMP”组合。</div>
<br>

<div style='width: 1000px;display:none;word-break: break-all;word-wrap: break-word;'>==mahuaBegin==c3fa46cf60542865e8dee78203e62ef50f1c6cfa2e4d86e64b917f2f2fb1f68f9c9cf5d48aca0e3884f738ffa11690e2c0d93459787d97d9ecf6dfdae7d193667091b68d08a1e67c1d82f91860652297bc78cfcb31e629976cd0ea68068567ee6405a127d8b6b3252abe78503eaaff971301fd50fef8c82202b7b512c7ccd60f5c103c1345501a4dc73a491d9acc29c1b4c642a4f6f71f96f855e10c887fb3be90a74a1627d1f370a81220e3cef0ad6617badb092717f724e21b35e5046b3fa0a8862c1c6c981de7e3a024c5d8549ca423fb1f93a9a26a8244a81995314f2dbf548cf1adccd301f000de2dea835f29c557e692561c3f43c4df52a9a6360fcde33c5a6f800ec5296aec5f30461e7bd5e99fd537caba6da8e209871151ba2ba97ec41aa629b8519d3c16e5e145130a0e70b985d39a65f758a3f1861b18f69fd134cd10f4521a8ce2f8e13069a80151b6ea6aa440268d9824ce0ab86bc53aa29db34444067c0ec0f551fc68513b91845391e204402d046c3ade095c93e2290fc51e4762a15678e46ce913d12346a3c48ba644566d66155fca675582ffb04126554fedb57da137da12960b2e942d132f73db==mahuaEnd==</ol>



<h2>系统特性</h2>
<ol>
<div>1．使用 C和 C++编写，并使用了多种编译器进行测试，保证了源代码的可移植性。</div>
<div>2．支持 AIX、FreeBSD、HP-UX、Linux、Mac OS、NovellNetware、OpenBSD、OS/2 Wrap、Solaris、Windows等多种操作系统。</div>
<div>3．为多种编程语言提供了 API。这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby,.NET和 Tcl 等。</div>
<div>4．支持多线程，充分利用 CPU 资源。</div>
<div>5．优化的 SQL查询算法，有效地提高查询速度。</div>
<div>6．既能够作为一个单独的应用程序应用在客户端服务器网络环境中，也能够作为一个库而嵌入到其他的软件中。</div>
<div>7．提供多语言支持，常见的编码如中文的 GB 2312、BIG5，日文的 Shift_JIS等都可以用作数据表名和数据列名。</div>
<div>8．提供 TCP/IP、ODBC 和 JDBC等多种数据库连接途径。</div>
<div>9．提供用于管理、检查、优化数据库操作的管理工具。</div>
<div>10．支持大型的数据库。可以处理拥有上千万条记录的大型数据库。</div>
<div>11．支持多种存储引擎。</div>
<div>12.MySQL 是开源的，所以你不需要支付额外的费用。</div>
<div>13.MySQL 使用标准的 SQL数据语言形式。</div>
<div>14.MySQL 对 PHP 有很好的支持，PHP是比较流行的 Web 开发语言。</div>
<div>15.MySQL是可以定制的，采用了 GPL协议，你可以修改源码来开发自己的 MySQL 系统。</div>
<div>16.在线 DDL/更改功能，数据架构支持动态应用程序和开发人员灵活性（5.6新增）</div>
<div>17.复制全局事务标识，可支持自我修复式集群（5.6新增）</div>
<div>18.复制无崩溃从机，可提高可用性（5.6新增）</div>
<div>19.复制多线程从机，可提高性能（5.6新增）</div>
<div>20.3倍更快的性能（5.7  新增）</div>
<div>21.新的优化器（5.7新增）</div>
<div>22.原生JSON支持（5.7新增）</div>
<div>23.多源复制（5.7新增）</div>
<div>24.GIS的空间扩展 （5.7新增）</div>
</ol>
</body>
</html>
