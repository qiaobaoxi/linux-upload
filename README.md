# linux-upload

  首先在linux里面创建一个文件夹
  
  然后在windows 端输入scp -r imocServer root@199.247.28.40:/work/server 就可以额
  
  有可能报 not a regular file 
  
  解决
  
  1：有可能没权限 chmod 777
  
  2:  在使用scp时加上-r 参数
  
    -p 拷贝文件的时候保留源文件建立的时间。 
    
    -q 执行文件拷贝时，不显示任何提示消息。 
    
    -r 拷贝整个目录   www.2cto.com  
    
    -v 拷贝文件时，显示提示信息
    
