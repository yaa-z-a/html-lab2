# 第二次作业：用户注册页面
## 作业内容
制作用户注册表单网页，包含三种列表、合并单元格的表格、多种表单控件。提交表单后，JS收集表单数据并打印在浏览器控制台。

## 使用到的标签
1. 语义化标签：header、main、footer
2. 列表：ul无序列表、ol有序列表、dl定义列表
3. 表格 table，使用 colspan 实现单元格跨列合并
4. 表单控件：text、password、radio、date、email、tel、checkbox、file、select、textarea、button
5. HTML5表单校验：required、minlength、maxlength、pattern手机号正则
6. JavaScript：监听表单submit事件，e.preventDefault()阻止页面刷新，FormData获取表单数据，console输出信息

## 遇到的困难及解决方法
1. 问题：表单点击提交页面会自动刷新，拿不到数据。
解决：添加 e.preventDefault() 阻止表单默认提交行为。
2. 问题：一开始CSS写在html内，需要拆分外部样式。
解决：把样式剪切到独立style.css，用link标签引入。
3. 问题：控制台出现 favicon.ico 404报错。
解决：该错误是缺少网页图标，不影响页面功能，直接忽略。
4. 问题：不知道怎么验证表单数据是否收集成功。
解决：F12打开开发者工具，切换Console面板，提交表单查看打印结果。
