# drawmap
根据一系列的经纬度坐标，利用百度地图开放平台的JavaScript API，绘制路径图

数据格式如xlsx文件所示，即为一连串的经纬度。
![image](https://user-images.githubusercontent.com/47874610/148897492-26532d1d-6b0a-4043-8fff-e7d1fd0b6b3f.png)

py文件是为了将xlsx文件中的一组经纬度，转换为这种格式：new BMap.Point(103.996118,30.766809),

最后在html文件上展示。

![image](https://user-images.githubusercontent.com/47874610/148897302-9307c738-a32b-49f1-908d-0b486c1c801c.png)

