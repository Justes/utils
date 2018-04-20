# 小工具

<a href="#cities">cities.sql</a><br />
<a href="#getfc">getfirstchar.php</a><br />


<a name="cities">cities.sql</a><br />
按照百度地图行政区划分，可直接导入数据库使用<br />
agb 为 百度地图返回的 adcode， 跟国家行政区划分一致<br />
level 为等级 ， 1省 2市 3区<br />
fc 为城市首字母， 只有 level 为 2 的才有值<br />

------

<a name="getfc">getfirstchar.php</a><br />
获取汉字首字母，将汉字传入函数 getfirstchar ，返回首字母， 有些字识别不了<br />
