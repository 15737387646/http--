项目结构：
               |-----httpserver   --HttpServer.py（主程序） 
      http--   |                  --settings (httpserver配置)
               |
               |        
               |
               |
               |-----WebFrame   --static(存放静态网页) 
                                --views.py   ( 应用处理程序)  
                                --urls.py   (存放路由)
                                --settings   (框架配置)
                                --WebFrame.py (主程序代码) 


功能:  
     httpserver:
       获取http请求
       解析http请求
       将请求发送给WebFrame
       从WebFrame接收反馈数据
       将数据组织为Response格式发送给客户端
     
    WebFrame:
       从httpserver接收具体请求
       根据请求进行逻辑处理和数据处理
           * 静态页面
           * 逻辑数据
       将需要的数据反馈给httpserver
