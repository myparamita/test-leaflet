
## tutorials
### 1. vectorTile.html
动态切片加载示例


## heatmap
### 1. heatmap-es-geohash.html
使用Elasticsearch的GeoHash grid Aggregation解决海量数据的热力图绘制问题

### 2. heatmap-es.html
查找ES中的数据，并使用heatmap.js显示热力图


## es
### 1. es-rest-ajax.html
ajax请求访问es提供的rest接口示例

### 2. es-rest-java.html
ajax请求java rest接口，java后台使用high rest api访问es提供的rest接口示例，
访问效率低于es-rest-ajax.html。

## pg
### 1. lbs_pg.html
ajax访问java rest请求；java rest服务中访问pg，查找指定点周围指定距离的点数据。


## s2(google s2 demo)
### 1. showCell10.html
查询并显示指定范围内level=10的cell

### 2. showPoints.html
查询并显示所有数据（es测试index：restaurants）

### 3. showPointsWithCell.html
- 查询当前点所在cell内的POI数据，显示当前cell范围，显示结果POI数据
- 使用s2索引方式查询1km范围内的POI数据，并显示1km范围对应的cell（包含优化方式和单一level索引2种）