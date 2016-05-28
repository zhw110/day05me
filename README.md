# day05me
JavaWeb -- day 05
1 观察http协议 
 
2 验证http响应头[只观察现象]

  (1)cn.itcast.web.http.Demo1：302+location=重定向

  (2)cn.itcast.web.http.Demo2：content-encoding:gzip(使用压缩格式的内容)
                               content-length:30(压缩内容长度)
			       GZIPOutputStream->ByteArrayOutputStream

  (3)cn.itcast.web.http.Demo3：content-type:(打开文件的类型)

  (4)cn.itcast.web.http.Demo4：content-disposition:(下载文件)

  (5)cn.itcast.web.http.Demo5：refresh：控制浏览器刷新

  (6)cn.itcast.web.http.Demo6：expires:-1或cache-control:no-cache或program:no-cache(禁止浏览器缓存)

3 cn.itcast.web.servlet.MyServlet：手工编写一个简单的Servlet程序[web.xml]

41 cn.itcast.web.servlet.Demo11：工具编写一个简单的Servlet程序[实现Servlet接口]
42 cn.itcast.web.servlet.Demo12：工具编写一个简单的Servlet程序[扩展GenericServlet类]
43 cn.itcast.web.servlet.Demo13：工具编写一个简单的Servlet程序[扩展HttpServlet类]

5 cn.itcast.web.servlet.Demo2：演示Servlet生命周期中各方法的执行情况
 
6 cn.itcast.web.servlet.Demo3：写一个自定义的缺省Servlet，用于处理无效的<url-pattern/>web资源的访问

7 cn.itcast.web.servlet.Demo4：演示Servlet线程安全问题及处理方案

8 cn.itcast.web.servlet.Demo5：通过ServletConfig获得在web.xml文件中配置的信息
