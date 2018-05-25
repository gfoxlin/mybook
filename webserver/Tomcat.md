# Mac install
* 通过ruby安装brew：
ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
* 安装Tomcat
    1. 搜索tomcat是否存在：brew search tomcat
    2. 安装tomcat：
        brew install tomcat
    3. 检查是否安装成功：
        catalina -h
    4. 运行tomcat：
        catalina run