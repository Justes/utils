# 小工具

cities.sql (#cities)
getfirstchar.php （#getfirstchar）


<span id="cities">按照百度地图行政区划分，可直接导入数据库使用</span>

agb 为 百度地图返回的 adcode， 跟国家行政区划分一致

level 为等级 ， 1省 2市 3区

fc 为城市首字母， 只有 level 为 2 的才有值

------

<span id="getfirstchar">getfirstchar.php</span>
获取汉字首字母，将汉字传入函数 getfirstchar ，返回首字母， 有些字识别不了
