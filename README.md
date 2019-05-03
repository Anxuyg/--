<h1>高德地图</h1>

<h6>创建它</h6>

<p>1. 进入官网，点击js API, 创建Key,得到Key值</p>
<p>2. 把key值放在指定的https链接中</p>
<p>3. 创建一个div标签，给它设置高度大小，方便容纳地图</p>
<p>4. 创建地图 new AMap.Map('div')</p>
<p>zoom: 11 //地图的级别，center: [11,11] //地图坐标</p>
<p>getZoom() //获取地图的级别，getCenter() //获取地图的中心位置</p>

<h6>方法</h6>
1. on('moveend') //地图移动结束时发生
2. on('zoomend') //地图级别发生改变时发生
