# BookShop_Learning
learning for bookshop
http://www.runoob.com/bootstrap/bootstrap-forms.html
1. Bootstrap，来自 Twitter，是目前最受欢迎的前端框架。Bootstrap 是基于 HTML、CSS、JAVASCRIPT 的，它简洁灵活，使得 Web 开发更加快捷。
2. <!-- jQuery文件。务必在bootstrap.min.js 之前引入 --> <script src="https://cdn.bootcss.com/jquery/2.1.1/jquery.min.js"></script>
     <!-- 最新的 Bootstrap 核心 JavaScript 文件 --> <script src="https://cdn.bootcss.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
3. 适配移动设备: <meta name="viewport" content="width=device-width, initial-scale=1.0">  //device-width用于呈现在不同的设备上，initial-scale:用于页面加载时原比例呈现。
    
<meta name="viewport" content="width=device-width, 
                                     initial-scale=1.0, 
                                     maximum-scale=1.0, 
                                     user-scalable=no">
4. 响应式图像：<img src="..." class="img-responsive" alt="响应式图像">
5. 使用 @font-family-base、 @font-size-base 和 @line-height-base 属性作为排版样式。
6.**网格结构**       a. <div class="container">...</div> 元素被添加，确保居中和最大宽度。
         *b. 一旦添加了容器，接下来您需要考虑以行为单位。添加 <div class="row">...</div>，并在行内添加列 <div class="col-md-6"></div>。*
         c. 网格中的每一行是由 12 个单元组成的，您可以使用这些单元定义列的尺寸。在我们的实例中，有两个列，每个列由 6 个单元组成，即 6+6=12
7. 在不同设备上的显示：<div class="col-sm-3 col-md-6 col-lg-4">....</div>  <div class="col-sm-9 col-md-6 col-lg-8">....</div>    //适用于三种不同的设备，手机、平板电脑、大型设备上的比例。
8.响应式的列重置：<div class="clearfix visible-xs"></div> *使用.clearfix 和响应式工具来解决*
9. 偏移列：使用.col-md-offset-* 类,将一个列的左边距增加* 列，* 的范围是1 到 11.
10. 缩写：<abbr title="World Wide Web">WWW</abbr><br>
11. 地址：<address></address>
12. 响应式表格：<div class="table-responsive"></div>
13. 超大屏幕：<div class="jumbotron"></div>
