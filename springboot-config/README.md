# SpringBoot配置文件demo

包括：

  1.基本字段的配置与注入
  
  2.实体类型的配置与注入
  
  3.配置文件（开发环境、生产环境等）的切换
  
测试：

  dev环境下：
  
    访问localhost:8089/GET/student测试基本字段注入
    
    访问localhost:8089/GET/demo测试实体注入
    
  prod环境下：
  
    与dev相同，将端口改为8080即可
