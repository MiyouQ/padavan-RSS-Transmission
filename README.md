这是一个在padavan路由上运行RSS订阅Transmission下载蜜柑计划新番的简易脚本。

理论上通用所有支持脚本的设备包含且不限于openwrt，ddwrt，tomato，群辉，梅林等，只需修改对应的<transmission/watch>目录
理论上支持所有.torrent(非磁链)下载站

保存违建后在Crontab里面设置定时
RSS_LINKS项内每行一个订阅链接
已下载的种子记录在/media/<U盘>/rss/downloaded_files.txt内
删除/mnt/transmission/watch内的种子文件不会影响重复下载检测