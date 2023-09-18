什么是SpringMVC
SpringMVC就是一个Spring内置的MVC框架。
MVC框架，它解决WEB开发中常见的问题(参数接收、文件上传、表单验证、国际化等等)，而且使用简单，与Spring无缝集成。支持 RESTful风格的URL请求。
采用了松散耦合可插拔组件结构，比其他 MVC 框架更具扩展性和灵活性。

SpringMVC的作用
MVC模式(Model-View-Controller)：解决页面代码和后台代码的分离。

SpringMVC原理
在没有使用SpringMVC之前我们都是使用Servlet在做Web开发。但是使用Servlet开发在接收请求参数，数据共享，页面跳转等操作相对比较复杂。
servlet是java进行web开发的标准，既然springMVC是对servlet的封装，那么很显然SpringMVC底层就是Servlet，SpringMVC就是对Servlet进行深层次的封装。

什么是mvc模式？
MVC分别是：模型model(javabean)、视图view(jsp/img)、控制器Controller(Action/servlet)。
C存在的目的就是为了保证M和V的一致性，当M发生改变时，C可以把M中的新内容更新到V中。

![Uploading image.png…]()
