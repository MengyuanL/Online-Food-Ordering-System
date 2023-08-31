1. # Online Food Ordering System based on SSM(Front-end+Back-end)
    
    #### Introduction
    
    Using Maven+Idea+Spring+SpringMVC+MyBatis+JSP 
    
    
    #### Installation
    
    1.  Database document：apsfc 20150727 2133.sql import database
    2.  Modify database info in `applicationContext.xml` file（Default database name：apsfc Username：root Password：123456）
    3.  Run 'mvc package' in root,put wrapped war package into '/webapp' in tomcat
    
    #### User guide
    
    Front-end：http://localhost:8080/qiantai
    Back-end：http://localhost:8080/admin
    
    meal_ordering_system  
    ├─ .gitignore  
    ├─ README.md  
    ├─ apsfc 20150727 2133.sql  
    ├─ pom.xml  
    └─ src  
           └─ main  
                  ├─ java  
                  │    └─ com  
                  │           └─ example  
                  │                  └─ meal_ordering_system  
                  │                         ├─ controller  
                  │                         │    ├─ AdminController.java  
                  │                         │    ├─ FileController.java  
                  │                         │    ├─ MainController.java  
                  │                         │    ├─ MenusController.java  
                  │                         │    ├─ NoticeController.java  
                  │                         │    ├─ OrdersController.java  
                  │                         │    ├─ TypesController.java  
                  │                         │    └─ UsersController.java  
                  │                         ├─ dao  
                  │                         │    ├─ AdminDao.java  
                  │                         │    ├─ MenusDao.java  
                  │                         │    ├─ NoticeDao.java  
                  │                         │    ├─ OrdersDao.java  
                  │                         │    ├─ TypesDao.java  
                  │                         │    └─ UsersDao.java  
                  │                         ├─ entity  
                  │                         │    ├─ Admin.java  
                  │                         │    ├─ Menus.java  
                  │                         │    ├─ Notice.java  
                  │                         │    ├─ Orders.java  
                  │                         │    ├─ Page.java  
                  │                         │    ├─ Pages.java  
                  │                         │    ├─ ShoppingCart.java  
                  │                         │    ├─ Types.java  
                  │                         │    └─ Users.java  
                  │                         ├─ interceptor  
                  │                         │    ├─ AdminLoginInterceptor.java  
                  │                         │    └─ UserLoginInterceptor.java  
                  │                         ├─ service  
                  │                         │    ├─ AdminService.java  
                  │                         │    ├─ MenusService.java  
                  │                         │    ├─ NoticeService.java  
                  │                         │    ├─ OrdersService.java  
                  │                         │    ├─ TypesService.java  
                  │                         │    ├─ UsersService.java  
                  │                         │    └─ impl  
                  │                         ├─ test  
                  │                         │    └─ testmybatis.java  
                  │                         └─ util  
                  │                                └─ AdviceUtil.java  
                  ├─ resources  
                  │    ├─ applicationContext.xml  
                  │    ├─ log4j.properties   
                  │    ├─ mapper  
                  │    │    ├─ AdminDao.xml  
                  │    │    ├─ MenusDao.xml  
                  │    │    ├─ NoticeDao.xml  
                  │    │    ├─ OrdersDao.xml  
                  │    │    ├─ TypesDao.xml  
                  │    │    └─ UsersDao.xml  
                  │    ├─ springMVC.xml  
                  │    └─ sqlMapConfig.xml  
                  └─ webapp  
                         ├─ WEB-INF   
                         │    └─ web.xml  
                         └─ public  
                                ├─ admin   
                                └─ qiantai    
    
