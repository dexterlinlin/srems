# 一 技术栈选择
## - **前端Vue的所有技术栈**： 
    vue
    elementUI
    d3
    axios 
## - **UI库**： 
   element-ui
## - **网络请求**：
   axios
## - **前端脚手架构建工具**：
   vue-cli
   
## - **联调工具**:
    Postman:https://dl.pstmn.io/download/latest/win64

## - **后端技术栈**：
    Django
    restfulframework:
       https://www.django-rest-framework.org/#requirements
       https://www.cnblogs.com/wuxl360/p/5787898.html
## - **对象图形框架**：
    py2neo.ogm
## - **数据库**：



     [neo4j](https://neo4j.com/docs/)
     mysql
     
## - **数据库连接池**
    sqlalchemy 
      https://my.oschina.net/gongju/blog/203142
      https://blog.csdn.net/zhutoucnn/article/details/45832103
## - **分布式**：
    
    
    
    Apache Flink
    
    Kafka
    
    Hadoop Yarn
   
---

# **二、开发环境准备** ：[参考链接](https://www.jianshu.com/p/9093894d2614)
## - 安装 <a href="https://nodejs.org/en/" target="_blank">NodeJS</a> ##
   
## - 安装Django ##   
    打开Anaconda Promt：
    activate yourvirtualenv
    pip install django 
    pip install -r requirements.txt
   
## - 安装VUE脚手架 ##
    打开cmd
    npm install -g cnpm --registry=https://registry.npm.taobao.org
    cnpm install -g vue-cli
   
---
   
# **三、初始化项目** :
## - 安装django脚手架 :
    打开Anaconda Promt：
    activate yourvirtualenv
    cd /d E:\Code\srems
    django-admin startproject sreapp
    cd sreapp
    python manage.py startapp sresvr
   

## - 安装vue脚手架 : 
    打开cmd
    cd /d E:\Code\srems\sreapp
    vue-init webpack sreclient
    cd sreclient
    cnpm install element-ui --save-dev
    cnpm install
    cnpm run build

## - 安裝<a href='https://www.cnblogs.com/libin-1/p/6607945.html' target="_blank">axios</a> 
    打开cmd
    cd /d E:\Code\srems\sreapp\sreclient
    cnpm install axios
   
## - 配置django url路径 :
    打开Anaconda Prompt
    cd /d E:\Code\srems\sreapp\sreserver
    
   


#  **后记/规划**  : 
    ```flow
    st=>start:开始
    op1=>operation:搭建项目骨架            doing 
    op2=>operation:neo4j建模(pymodel/ogm) doing
    op3=>operation:vue增删改neo4j
    op4=>operation:d3展示neo4j
    op5=>operation:d3增删改neo4j
    op6=>.....
    str ->op1 -> op2 -> op3 -> op4 -> op5 -> op6
    &```

---


#  杂项(待整理):
## 2019-3-31:
    FrontEnd:VueJS d3
    WebFramework:bottle django
    DB: Neo4j (https://neo4j.com/docs/)
    OGM: pyneo4jogm

    Later： spark + neo4j

    Export requirement： pip freeze > requirements.txt

    remaining question: 
    1. how to display topology in web
    2. how to display chinese words properly in web
    3. ....


    generate ssh-key: 
    ssh-keygen -t rsa -C "your_email@example.com"
    
    2019-4-1：
    clear neo4j database：
      match (n)
      detach delete n
      
    markdown 基本语法：https://www.jianshu.com/p/191d1e21f7ed
    cat xxxx | grep -iE xxx~~
    
    
    Pycharm一直Indexing：File-Invalidate/Restart
    使用cmder替代cmd：https://cmder.net/
    
    Python设计模式:https://www.cnblogs.com/Liqiongyu/p/5916710.html
    