<pre>
# VueTest
针对vue.js开发的一些组件示例

一、VueTest 项目实现功能
1. 无限分级菜单组件：Menu.vue
2. Grid 组件： Grid.vue
3. 分页组件： Pagination.vue （ 添加pageSizeList: [10,20,30,40,50,60] 设置每页显示记录数 ）
4. 查询组件：FilterPane.vue
5. 2-3-4 合并成GridBase组件，其中 TestGrid.vue, User.vue 使用GridBase组件来改写。
6. VueStrap 的使用示例：TestVueStrap.vue

二、数据来源：
数据通过mock.js 生成，然后用json-server 来管理根目录下的db.json，模拟后端数据库，
产生restful api, 供前端调用。Restful api 可以通过localhost:8080/api/访问。所以现在看到的
testgrid, user 页面，基本上和访问后端数据库一样，可以完全模拟访问后端api。

三、访问：
运行r.bat 就可以启动服务进行访问。
访问localhost:8080/api/可以访问json-server 的api.
访问localhost:8080/app/index.html, 可以访问示例程序。

运行效果可以参考Img目录下的图片。

</pre>
