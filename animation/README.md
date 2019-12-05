## CSS动画
CSS动画共有八种属性和一个八种属性集合的简短属性缩写。
1. 若没有开头结尾，会自动演算出来
2. 不可单独使用数字，一定要加入 %
3. 如果同样的百分比，则相同属性会后盖前


属性 | 说明
---|---
animation-name | 动画名称
animation-duration | 动画持续时间，**预设0**，单位s或ms
animation-timing-function | 动画加速度函数，**预设ease**，其他还有：linear、ease-in、ease-out、ease-in-out、step-start、step-end、steps(int,start/end)、cubic-bezier(n,n,n,n)
animation-delay | 动画延迟播放时间，**预设0**，单位s或ms
animation-iteration-count | 动画播放次数，**预设1**，其他还有：infinite
animation-direction | 动画播放方向，**预设none**，其他还有：reverse、alternate、alternate-reverse
animation-fill-mode | 动画播放后模式，**预设none**，其他还有：forwards、backwards、both
animation-play-state | 动画播放或暂停状态，**预设running**，其他还有：paused


这八种属性，亦可透过animation 的属性，做简短的缩写，用法如下：
```css
animation:name duration | timing-function | delay | iteration-count | direction | fill-mode | play-state;
```