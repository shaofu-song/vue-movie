# vue-movie-demo

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### 项目介绍：
  * 该项目实现城市定位、电影列表及详情页展示、搜索框功能(需用拼音搜索)和城市部分影院列表的功能。
### 实现技术：
  * 1.使用vue-cli构建项目。
  * 2.使用vue-router进行项目路由配置。
  * 3.使用axios获取API接口数据，对各组件进行数据渲染。
  * 4.使用vuex处理各组件间的通讯，进行状态管理。
  * 5.封装better-scroll和loading组件实现上拉加载和正在加载效果。
  * 6.城市页面右侧实现了地址索引功能。
### 数据API接口：
  * 正在热映
      * http://39.97.33.178/api/movieOnInfoList?cityId=10
  * 即将上映
      * http://39.97.33.178/api/movieComingList?cityId=10
  * 搜索
      * http://39.97.33.178/api/searchList?cityId=10&kw=a
  * 城市
      * http://39.97.33.178/api/cityList
  * 电影详情
      * http://39.97.33.178/api/detailmovie?movieId=345808
  * 影院
      * http://39.97.33.178/api/cinemaList?cityId=10
  * 城市定位
      * http://39.97.33.178/api/getLocation

  
