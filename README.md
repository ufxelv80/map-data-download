# map-data-download

### 地图瓦片数据下载工具
- 基于 React18 + Electron 开发的地图瓦片数据下载工具


- [x] 支持必应地图山歌瓦片
- [x] 支持百度地图矢量瓦片
- [ ] 百度地图栅格瓦片待开发
- [ ] 高德地图栅格瓦片待开发
- [ ] 天地图地图栅格瓦片待开发

```text
下载必应地图瓦片数据时会同时下载地图的 poi 点，由于 poi 点和瓦片是分开的，所以使用时需要另起服务来代理 poi 点，后续会提供 必应地图的离线 API 以及 poi 代理服务
```
```text
下载百度地图时由于百度地图的是矢量瓦片所以不会默认下载 poi 点，如果地图需要设置个性化地图请不要勾选 包含 poi 点, 如果不是个性化地图请勾选 包含 poi 点
```


![Alt text](images/1.png?raw=true "Optional Title")
![Alt text](images/2.png?raw=true "Optional Title")

