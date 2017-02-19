# 关于CSS百分比相对于谁的疑问

# 相对于父元素宽度

- width
- left
- right
- padding
- margin 


        ps: [max-/min-]也包括在内。


# 相对于父元素高度
- height
- top
- bottom

        ps: [max-/min-]也包括在内。


# 相对于父元素字号
- font-size

# 相对于父元素自身字号
- line-height

# 相对于自身宽高
- border-radius
- background-size
- transform: translate()
- transform-origin
- zoom
- clip-path

# 特殊算法
- background-position（方向长度 / 该方向除背景图之外部分总长度 * 100）
- filter 系列函数
- position: fixed（相对视口）
- position: absolute（相对于距离它最近的祖先'positioned'元素 ）

        什么是'positioned'元素 ？
        将position设置为static以外的值的元素称为'positioned'元素      




