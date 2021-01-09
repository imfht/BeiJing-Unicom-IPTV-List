# 北京联通IPTV频道列表

## 列表介绍

这是一份通过模拟登陆获取的北京联通IPTV频道列表，不存在非官方频道，与联通IPTV盒子内的直播列表基本一致，与通过[扫描](https://github.com/sdhzdmzzl/iptv_channel_scanner_windows)获取的频道列表可能有少许不同

本列表的相关代码部署在路由器上，每小时执行一次，检测到列表发生变化后自动将更新后的列表同步至GitHub，因此本列表可能是网上更新最及时的北京联通IPTV频道列表了，其提交历史在一定程度上也可以看作是联通IPTV频道的更新历史

我也会不定期根据个人喜好对列表内的频道顺序进行调整，主要原则和排列顺序是：CCTV高清->北京高清->卫视高清->其他高清->标清->测试

官方列表内存在个别名称相同、分辨率码率基本一致，但存在差异的频道，为方便区分，本列表分为两个版本（均保留所有差异频道）：

* iptv.m3u，频道名不带频道号

* iptv_ChannelID.m3u，频道名带频道号


## 使用教程

由于IPTV是局端控制，因此如果你和我不是一个分局（西直门），本列表你可能用不了，如果能使用，请下载并编辑iptv.m3u文件：

* 如果使用udpxy，那么直接将“`192.168.11.1:8888`”替换为你本地的路由器地址和udpxy端口并保存后就可以使用了

* 如果没用使用udpxy，或想直接使用rtp地址，那么将“`http://192.168.11.1:8888/rtp/`”替换为“`rtp://`”并保存后就可以使用了


## 其他

* 官方列表内存在个别无法播放的频道地址，本列表暂时没有去除

* 即使是相同分局，也可能存在组播地址不一致的情况，请定期连接并更新联通的官方盒子，不要一直吃灰

* 抓取频道的代码存在失效的可能，如果发现列表没有及时更新，请尽快反馈，谢谢
