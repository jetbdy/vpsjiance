#service_count
![table](http://git.oschina.net/uploads/images/2016/1202/134105_2a403897_700748.png "界面")

cron.sh文件 crontab定时执行
1分钟发送一次；

crontab设置
>chmod +x cron.sh
>crontab -e 
添加一条记录
>*/1 * * * * /your_dir/cron.sh

cron.sh文件
修改
>POST_URL=127.0.0.1/tongji.php //你的统计文件脚本
>TOKEN=www//验证的KEY

tongji.php文件
修改
>define('USER', "root");//数据库用户名
>define('PASS', "jet0508");//数据库密码
>define('DB', "vps");//数据库名
>define('KEY', "www");//验证KEY
>define('PA', "www");//如果设置了密码，只有输入密码才能访问
 

bash由来自悠久的翼