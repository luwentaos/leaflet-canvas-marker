# leaflet-canvas-marker

### 方法说明

```
addLayers 绘制一组markers
setOptions 设置图层参数
clearLayers 清除所有的
_redraw 重绘画布
```

### 参数说明

| 参数       | 默认值     | 说明                                                         |
| ---------- | ---------- | ------------------------------------------------------------ |
| moveReset  | null       | 在 move 时是否刷新地图                                       |
| opacity    | 1          | 图层透明度                                                   |
| pane       | markerPane | 图层所在 leaflet 层                                          |
| onUserDraw | null       | 自定义绘制样式（用 canvas）marker 自定义的参数 properties={} |
