# xSlider for jQuery 轮播图插件

### preview

![预览图](./preview.jpg)

### 用法说明

- html

  ``` html
  <div class="slider">
    <div class="slider-img">
      <ul class="slider-img-ul">
        <li><img src="images/slider-5.jpg"></li>
        <li><img src="images/slider-1.jpg"></li>
        <li><img src="images/slider-2.jpg"></li>
        <li><img src="images/slider-3.jpg"></li>
        <li><img src="images/slider-4.jpg"></li>
        <li><img src="images/slider-5.jpg"></li>
        <li><img src="images/slider-1.jpg"></li>
      </ul>
    </div>
  </div>
  ```

- css

  > [压缩版](/build/xSlider.min.css) / [开发版scss](/build/xSlider.scss)

- javascript

  ``` javascript
  // 初始化xSlider,可选参数config
  $('.slider').xSlider()
  ```



### 可选参数

| config        | 说明                    | 默认属性        |
| ------------- |------------------------| -------------- |
| w             | 轮播图宽度               | .slider的宽度   |
| current       | 默认显示第n张图（从0开始） | 0              |
| speed         | 图片切换速度             | 500            |
| intervalTime  | 自动切换时长             | 5000           |
