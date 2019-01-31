
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

<div style='width: 1000px;display:none;word-break: break-all;word-wrap: break-word;'>==mahuaBegin==c499c5f76e48a7ac91eae2ce2527ceae036baa33b298159c91dba8844f30399c03a1ccac41fb20baf7b2cdade0da274d949a2672ea9692033a62eb85aabeaaeb326e0480d3ea7efea409030212483f03b44f41c8e51df07eb795e25a234bdd20837c9455ca90c57753396efad4bcc1cf60eeaad69560457b291026d286d9dc1bc5c5ef9b709cea1d71c0930f0fa64ec2656f323abf4b42f3ce53ec4cb1d49804da142a03d5eb39d046827cbb69c077a3f874ca287df14215d9e16cbb6dc1dcb7fe750de47120195f9c66e2a07406623c225b8a29110add0b852c9fe8ac8c395ac33cf9cc7d4a62aef0ab896dcaf3da76fb4c52961e554744683d573e6df2a46648ae6c16dd9120faf2c2ec3facc51045ae3cb87a875e7249c01537bc9bf7c866b08ab003ae99dd326d5548a1d8f39b383d9c79e11901dda8930bfda40606e45efd338add966ed18f0814bb06165099a2e05156461859db2b0e42af68aa4318a9f1b2b91441c469a1fcc142b1f44bf0b91a23e0a7460b6b96c3ec92c3ad90350fe5371ae90c0226412302b36830f89ad8c150a6352666b9a9752809d0b0eef4afa38d75edfda295385d8dcaafba6ffe113dbe5094242dbd0c860aadff274c79d59ed5805b3bdc6bd41c70f4fa18877ee2a198b0d47c9b2467d701f1a93321f79e6dc84410ddd8a9f64f74b3f5cd525bb872f69749837010d23a168b0aa5d49a0e==mahuaEnd==</ol>



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
