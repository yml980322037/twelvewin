本仓库包括一个基于python和flask框架开发的股票分析平台，该平台利用tushare库获取股市的实时行情、历史行情以及个股相关财务数据，结合scrapy爬取雪球的个股年报财务数据，通过pandas库对数据进行统计分析，得到个股的以下信息：
1. 基本面信息，如市盈率、市净率、净资产收益率和现金收益率排名；
2. 技术面信息，筛选历史新高、新低，均线多头、突破20日均线以及年线之上的个股；
3. 板块分类，通过scikit learn的聚类算法对上证50、中证500和沪深300进行聚类分析；
4. 行业分析，通过以上相同的聚类算法对行业个股进行基本面和技术面的聚类分析；

另外还包含个股查询，如查看个股的基本面数据和K线数据。
访问网站: www.twelvewin.com

