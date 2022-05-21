# home-page
v2b的index.html <br>
部署方法 <br>
进入v2Board的运行目录： <br>

cd /usr/share/nginx/html/v2board/public/ <br>
宝塔：cd /www/wwwroot/网站目录/public/    <br>

下拉首页文件： <br>

git clone https://github.com/besnow/home-page.git   <br>
mv home-page/* .    <br>
修改Nginx运行的index优先级： <br>

index index.html index.htm index.php; <br>
若是宝塔搭建的，自行修改配置文件，将index.html放在第一，其他往后移。 <br>
宝塔修改可参考：https://jingyan.baidu.com/article/7e440953f70e516ec0e2efc0.html
