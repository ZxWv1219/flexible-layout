### 一. 如果写了弹性盒

父元素

```css
 {
  display: flex;
}
```

### 二. 容器属性

- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items

#### flex-direction 决定主轴的方向(即项目的排列方向)

![1594342833_1_.jpg](https://i.loli.net/2020/07/10/soeSKw4jUZRGLJH.png)

#### flex-wrap

![1594343856_1_.jpg](https://i.loli.net/2020/07/10/d6uvwZjLBm3OSqe.png)

#### flex-flow

它就是 direction 与 wrap 的结合 flex-flow: column wrap

#### justify-content 属性定义了项目在主轴上的对齐方式(水平排列)

```css
.box {
  justify-content: flex-start|flex-end|center|space-between|space-around;
}
```

![1594344474_1_.jpg](https://i.loli.net/2020/07/10/te5PcO4L9WQCHB6.png)

#### align-items 定义项目在交叉轴上如何对齐(垂直排列)

```css
.box {
  align-items: flex-start|flex-end|center|baseline|stretch;
}
```

### 三. 项目的属性

- flex-grow
- flex-shrink
- flex-basis
- flex

#### flex-grow

定义项目的放大比例,默认值 0, 即如果存在剩余空间, 也不放大

#### flex-shrink

超出空间大小后, 定义项目的缩小比例,默认值 0, 即如果存在剩余空间, 也不放大

#### flex-basis

定义了在分配多余空间之前, 项目占据的主轴空间(main size)

#### flex

flex 属性是 flex-grow, flex-shrink, flex-basis 的简写,默认值 0 1 auto,后两个属性可选

### 单位尺寸
- px
- % (继承自父元素,当父元素无宽高的情况下是没有效果的)
- vw 视口,窗口
- vh
- em  针对于父元素的font-size(1em=parent.font-size)
- rem 选对于根元素(html), 移动端常用

谷歌浏览器默认字体大小: 16px

### 