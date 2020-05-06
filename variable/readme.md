##  css 表示能力很强，  现代变革让css具有了编程语言的能力，请问哪些方面或技术可以让css 更具程序表达能力？

stylus 变量定义 嵌套  函数

- css4 推出了 css variable 能力， 可以实现stylus()一样的效果， css4是原生支持的。
    stylus 在头部定义变量  variable = value
    把变量集中在头部定义， 方便修改和管理
    stylus 并不需要 $ 但我们使用 $ 有良好的编程风格， php $variable

-   css3 css4
    css3 的新特性：
    animation(复杂动画设计) transition(css属性修改带来过渡)
    translate3d transform
    box-shadow flex linear-gradient
    rgba() 带有透明属性
    grid 布局  filter

-   弹性布局 flex
    三栏布局， 传统的双飞翼布局， 圣杯布局可以，
    flex 布局也可以
    main 放到第一位  优先实现， 用户先看到主题内容，最重要
    页面我们看到是绘制出来的 绘制页面 （布局，大小，颜色）需要时间， main区域重要，优先绘制很重要。
    眼睛感觉的时间差60fps

    order: -1; position/靠前
