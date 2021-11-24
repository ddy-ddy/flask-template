### 这是一个flask web项目的模板

```bash
.
├── README.md
├── data.db
├── dy_app                  //程序包
│   ├── __init__.py   //包构造文件,创建程序实例
│   ├── commands.py   //命令函数
│   ├── errors.py     //错误处理函数
│   ├── models.py     //模型类
│   ├── static        //存放css,js,图片等 
│   │   ├── css
│   │   ├── favicon.ico
│   │   ├── images
│   │   │   ├── avatar.png
│   │   │   └── totoro.gif
│   │   └── style.css
│   ├── templates      //html模板
│   │   ├── base.html   //基本的html,其他html可以继承这个html
│   │   ├── edit.html
│   │   ├── errors   //错误页面的html
│   │   │   └── 404.html
│   │   ├── index.html
│   │   ├── login.html
│   │   └── settings.html
│   └── views.py     //视图函数
├── run.py   //运行入口
└── test_dy_app.py     //测试项目代码
```

