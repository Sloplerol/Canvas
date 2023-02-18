# Canvas
Canvas是HTML5提供的一项API，它允许开发者通过JavaScript在网页上创建和操作图形、动画以及游戏等视觉效果。通过Canvas，开发者可以使用各种绘制方法和属性，例如绘制形状、文字、图片，以及应用颜色、渐变、阴影等特效。Canvas可被用于创建动态的、交互式的Web应用程序，并且由于其高性能和可扩展性，Canvas在Web开发中被广泛应用。


### Canvas实现数据可视化
  * 什么是可视化？
    > 数据可视化是指将数据以图形、图表、地图等可视化形式展现出来的过程
  * Canvas的特征
    * H5新增特性
    * 默认宽高为300*150
    * 浏览器内部将其视为图片
    * 通过属性来设置画布的宽和高
    ```<canvas width="" height=""></canvas>```
    * 操作Canvas需要通过js来实现
    ```
    let canvas = document.querySelector('canvas');
    //获取到笔
    let ctx = canvas.getContext('2d');
    //设置起点
    ctx.moveTo(100,100)
    //设置其他点
    ctx.lineTo(200,200)
    //绘制线段
    ctx.stroke()
    //连接起点和终点
    ctx.closePath()
    //设置填充颜色
    ctx.fillStyle = "red";
    ctx.fill()
    //设置线段颜色
    ctx.strokeStyle = "pink";
    //设置线段m宽度
    ctx.lineWidth = "20";
    ```
### Summary
   * ✨ Canvas数据可视化帮助我们通过形象的方式呈现数据总体流向
   * 🕓 Canvas难度不大 大部分集中在坐标计算上
   * 🌞 面向未来 未来的发展将会更加丰富和多样化，可以为各行业的开发者提供更好的可视化工具和应用场景。
   * 🖌 鼓励读者勇于尝试 多去书写 
    
