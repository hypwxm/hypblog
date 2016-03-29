#安装express代码生成器
>npm install -g express-generator
#生成项目  应用ejs模板
>express -e hypblog
#进入目录并安装依赖项  会根据package.json里面的dependence自动安装依赖
>cd hypblog && npm install
#设置环境变量并启动服务器  start启动的是package.json里面的scripts属性的start所对应的路径的文件的启动端口。默认3000
>SET DEBUG=hypblog:* & npm start
#通过浏览器访问
localhost:3000